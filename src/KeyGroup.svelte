<script>
	export let cssClass = '';
</script>

<style type="text/scss">
	.key-group {
		&:not(:first-child) {
      margin-left: var(--gap-size);
    }
	}
</style>

<div class={`key-group ${cssClass}`}>
	<slot></slot>
</div>
