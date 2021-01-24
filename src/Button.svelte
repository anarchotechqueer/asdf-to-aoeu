<script>
	export let text = 'start';
  export let clickEvent;

  const buttonHandler = (e) => {
    clickEvent();
    const el = e.target;
    el.parentNode.removeChild(el);
  }
</script>

<style type="text/scss">
.button {
  width: calc(var(--key-outline-size) * 4);
  height: var(--key-outline-size);
  border-radius: 1.7mm;
  border: var(--key-outline-border-size) solid var(--color-black);
  background-color: transparent;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-transform: uppercase;
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  margin: 0;
  margin-bottom: var(--gap-size);
  transition-duration: .25s;
  transition-property: color, background-color;
  cursor: pointer;

  &:hover,
  &:focus {
    color: white;
    background-color: var(--color-black);
  }
}
</style>

<button class="button" on:click|once={(e) => {buttonHandler(e);}}>
	{text}
</button>
