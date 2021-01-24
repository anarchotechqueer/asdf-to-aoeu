<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyGroup from './KeyGroup.svelte';
  import Key from './Key.svelte';

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

    <Key outlineCssClass={'key-outline--arrow key-outline--arrow--horizontal'} cssClass={'key--arrow key--arrow--left'} />

    <KeyGroup>
      <Key outlineCssClass={'key-outline--arrow key-outline--arrow--top key-outline--gapless'} cssClass={'key--arrow key--arrow--up'} />
      <Key outlineCssClass={'key-outline--arrow key-outline--arrow--bottom key-outline--gapless'} cssClass={'key--arrow key--arrow--down'} />
    </KeyGroup>

    <Key outlineCssClass={'key-outline--arrow key-outline--arrow--horizontal'} cssClass={'key--arrow key--arrow--right'} />
  </KeyboardRowInner>
</KeyboardRow>
