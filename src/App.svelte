<script>
	import Keyboard from './Keyboard.svelte';
	import KeyboardRowUtil from './KeyboardRowUtil.svelte';
	import KeyboardRow1 from './KeyboardRow1.svelte';
	import KeyboardRow2 from './KeyboardRow2.svelte';
	import KeyboardRow3 from './KeyboardRow3.svelte';
</script>

<style>

</style>

<Keyboard>
	<KeyboardRowUtil />
	<KeyboardRow1 />
	<KeyboardRow2 />
	<KeyboardRow3 />


<!-- 	<KeyboardRow>
		<KeyboardRowInner>
		</KeyboardRowInner>
	</KeyboardRow>

	<KeyboardRow>
		<KeyboardRowInner>
		</KeyboardRowInner>
	</KeyboardRow>

	<KeyboardRow>
		<KeyboardRowInner>
		</KeyboardRowInner>
	</KeyboardRow>

	<KeyboardRow>
		<KeyboardRowInner>
		</KeyboardRowInner>
	</KeyboardRow>

	<KeyboardRow>
		<KeyboardRowInner>
			 <div>hi</div>
		</KeyboardRowInner>
	</KeyboardRow>

	<KeyboardRow>
		<KeyboardRowInner>
		</KeyboardRowInner>
	</KeyboardRow> -->
</Keyboard>
