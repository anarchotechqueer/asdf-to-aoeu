<script>
	import Keyboard from './Keyboard.svelte';
	import KeyboardRowUtil from './KeyboardRowUtil.svelte';
	import KeyboardRow1 from './KeyboardRow1.svelte';
	import KeyboardRow2 from './KeyboardRow2.svelte';
	import KeyboardRow3 from './KeyboardRow3.svelte';
	import KeyboardRow4 from './KeyboardRow4.svelte';
	import KeyboardRow5 from './KeyboardRow5.svelte';
	import KeyboardRowFreeSpaces from './KeyboardRowFreeSpaces.svelte';

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
</Keyboard>
