<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineCssClass={'key-outline--fn'} keyText={['fn']} />

    <Key outlineCssClass={'key-outline--control'} keyText={['control']} />

    <Key outlineCssClass={'key-outline--option key-outline--option--left'} keyText={['alt', 'option']} />

    <Key outlineCssClass={'key-outline--cmd key-outline--cmd--left'} keyText={['⌘', 'command']} />

    <Key outlineCssClass={'key-outline--space'}/>

    <Key outlineCssClass={'key-outline--cmd key-outline--cmd--right'} keyText={['⌘', 'command']} />

    <Key outlineCssClass={'key-outline--option key-outline--option--right'} keyText={['alt', 'option']} />

    <!-- add arrow keys here -->
  </KeyboardRowInner>
</KeyboardRow>
