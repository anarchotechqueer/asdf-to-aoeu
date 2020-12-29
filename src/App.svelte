<script>
	import Keyboard from './Keyboard.svelte';
	import KeyboardRow from './KeyboardRow.svelte';
	import KeyboardRowInner from './KeyboardRowInner.svelte';
	import KeyOutline from './KeyOutline.svelte';
	import Key from './Key.svelte';
	import KeyText from './KeyText.svelte';
</script>

<style>

</style>

<Keyboard>
	<KeyboardRow cssClass={'keyboard-row--util'}>
		<KeyboardRowInner cssClass={'key'}>
			<KeyOutline location={''}>
				<Key cssClass={''}>
					<KeyText text={'hi'}></KeyText>
				</Key>

			</KeyOutline>

		</KeyboardRowInner>
	</KeyboardRow>

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
