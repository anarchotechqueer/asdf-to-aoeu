<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import Key from './Key.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner cssClass={'keyboard-row__inner--spaced'}>
    <Key location={'free-space-1'} />
    <Key location={'free-space-2'} />
  </KeyboardRowInner>
</KeyboardRow>
