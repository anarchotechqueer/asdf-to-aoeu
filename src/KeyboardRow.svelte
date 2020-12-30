<script>
	export let cssClass;
</script>

<style type="text/scss">
.keyboard-row {
  display: flex;
  justify-content: center;
  width: 1086px;
  margin: 0 auto;

  &:not(:first-child) {
    margin-top: var(--gap-size);
  }

  
}
</style>

<div class={`keyboard-row ${cssClass}`}>
	<slot></slot>
</div>
