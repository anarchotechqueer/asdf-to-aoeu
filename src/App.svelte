<script>
	import { onMount } from 'svelte';
	import anime from 'animejs/lib/anime.es.js';
	import Keyboard from './Keyboard.svelte';
	import KeyboardRowUtil from './KeyboardRowUtil.svelte';
	import KeyboardRow1 from './KeyboardRow1.svelte';
	import KeyboardRow2 from './KeyboardRow2.svelte';
	import KeyboardRow3 from './KeyboardRow3.svelte';
	import KeyboardRow4 from './KeyboardRow4.svelte';
	import KeyboardRow5 from './KeyboardRow5.svelte';
	import KeyboardRowFreeSpaces from './KeyboardRowFreeSpaces.svelte';
	import Button from './Button.svelte';
	import {animationData, transitionTime} from './lib/animationData.js';

	const animateKey = (keyIndex = 0) => {
	  const {key, loc} = animationData[keyIndex];

	  const keySelector = `[data-animate="${key}"]`;
	  const locationSelector = `[data-location="${loc}"]`;

	  const keyItem = document.querySelector(keySelector);
	  const keyParent = keyItem.parentNode;
	  const keyBounds = keyParent.getBoundingClientRect();

	  const location = document.querySelector(locationSelector);
	  const locationBounds = location.getBoundingClientRect();

	  var xDiff = locationBounds.x - keyBounds.x;
	  var yDiff = locationBounds.y - keyBounds.y;

	  var locationDiff = {
	    x: xDiff,
	    y: yDiff,
	  };

	  keyItem.addEventListener("transitionend", () => {
	    keyItem.classList.add('key--active');

	    anime({
	      targets: keyItem,
	      translateX: locationDiff.x,
	      translateY: locationDiff.y,
	      easing: 'cubicBezier(.5, .05, .1, .3)',
	      duration: 100,
	      complete: function(anim) {
	        keyItem.classList.remove('key--active');
	        keyItem.classList.remove('key--selected');

	        if (keyIndex < animationData.length - 1) {
	          animateKey(++keyIndex);
	        }
	      },
	    });
	  },{'once': true});

	  keyItem.classList.add('key--selected');
	};

	const handleClick = () => {
		animateKey();
	}

</script>

<style type="text/scss">

</style>

<Keyboard>
	<KeyboardRowUtil />
	<KeyboardRow1 />
	<KeyboardRow2 />
	<KeyboardRow3 />
	<KeyboardRow4 />
	<KeyboardRow5 />
	<KeyboardRowFreeSpaces />
	<Button clickEvent={handleClick}/>
</Keyboard>
