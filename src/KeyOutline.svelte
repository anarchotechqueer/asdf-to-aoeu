<script>
	export let location;
</script>

<style type="text/scss">
.key-outline {
  width: var(--key-outline-size);
  height: var(--key-outline-size);
  border-radius: 1.7mm;
  border: var(--key-outline-border-size) solid var(--color-black);
  flex-grow: 0;
  flex-shrink: 0;

  &:not(:first-child) {
    margin-left: var(--gap-size);
  }
}
</style>

<div class={`key-outline`} data-location={location}>
	<slot></slot>
</div>
