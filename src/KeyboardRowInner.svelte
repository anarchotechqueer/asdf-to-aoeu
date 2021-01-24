<script>
	export let cssClass = '';
</script>

<style type="text/scss">
.keyboard-row__inner {
	display: flex;
	width: 100%;

	&--spaced {
		justify-content: space-between;
	}
}
</style>

<div class={`keyboard-row__inner ${cssClass}`}>
	<slot></slot>
</div>
