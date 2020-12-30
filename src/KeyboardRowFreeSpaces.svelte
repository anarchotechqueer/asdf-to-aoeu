<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner cssClass={'keyboard-row__inner--spaced'}>
    <KeyOutline location={'free-space-1'} />
    <KeyOutline location={'free-space-2'} />
  </KeyboardRowInner>
</KeyboardRow>
