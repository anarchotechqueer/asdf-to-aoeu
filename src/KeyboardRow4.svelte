<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import Key from './Key.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineLocation={'r4-1'} outlineCssClass={'key-outline--shift key-outline--shift--left'} keyText={['shift']} />

    <Key outlineLocation={'r4-2'} animateIndex={12} keyText={['z']} />

    <Key outlineLocation={'r4-3'} animateIndex={3} keyText={['x']} />

    <Key outlineLocation={'r4-4'} animateIndex={25} keyText={['c']} />

    <Key outlineLocation={'r4-5'} animateIndex={33} keyText={['v']} />

    <Key outlineLocation={'r4-6'} animateIndex={4} keyText={['b']} />

    <Key outlineLocation={'r4-7'} animateIndex={5} keyText={['n']} />

    <Key outLinelocation={''} keyText={['m']} />

    <Key outlineLocation={'r4-8'} animateIndex={19} keyText={['<', ',']} />

    <Key outlineLocation={'r4-9'} animateIndex={21} keyText={['>', '.']} />

    <Key outlineLocation={'r4-10'} animateIndex={13} keyText={['?', '/']} />

    <Key outlineLocation={'r4-11'} outlineCssClass={'key-outline--shift key-outline--shift--right'} keyText={['shift']} />
  </KeyboardRowInner>
</KeyboardRow>
