<script>
	export let cssClass;
	export let animateIndex;
</script>

<div class={`key ${cssClass}`} data-animate={animateIndex}>
	<slot></slot>
</div>
