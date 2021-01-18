<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key keyText={['~', '`']} />

    <Key keyText={['!', '1']} />

    <Key keyText={['@', '2']} />

    <Key keyText={['#', '3']} />

    <Key keyText={['$', '4']} />

    <Key keyText={['%', '5']} />

    <Key keyText={['^', '6']} />

    <Key keyText={['&', '7']} />

    <Key keyText={['*', '8']} />

    <Key keyText={['(', '9']} />

    <Key keyText={[')', '0']} />

    <Key outlineLocation={'r1-12'} animateIndex={15} keyText={['_', '-']} />

    <Key outlineLocation={'r1-13'} animateIndex={16} keyText={['+', '=']} />

    <Key cssClass={'key--delete'} outlineCssClass={'key-outline--delete'} keyText={['delete']} />
  </KeyboardRowInner>
</KeyboardRow>
