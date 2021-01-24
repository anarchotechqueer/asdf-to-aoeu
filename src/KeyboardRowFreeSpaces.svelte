<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import Key from './Key.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner cssClass={'keyboard-row__inner--spaced'}>
    <Key outlineOnly={true} outlineLocation={'free-space-1'} />
    <Key outlineOnly={true} outlineLocation={'free-space-2'} />
  </KeyboardRowInner>
</KeyboardRow>
