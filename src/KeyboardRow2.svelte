<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineLocation={'r2-1'} cssClass={'key--tab'} outlineCssClass={`key-outline--tab`}  keyText={['tab']} />

    <Key outlineLocation={'r2-2'} animateIndex={1} keyText={['q']} />

    <Key outlineLocation={'r2-3'} animateIndex={18} keyText={['w']} />

    <Key outlineLocation={'r2-4'} animateIndex={20} keyText={['e']} />

    <Key outlineLocation={'r2-5'} animateIndex={8} keyText={['r']} />

    <Key outlineLocation={'r2-6'} animateIndex={31} keyText={['t']} />

    <Key outlineLocation={'r2-7'} animateIndex={30} keyText={['y']} />

    <Key outlineLocation={'r2-8'} animateIndex={28} keyText={['u']} />

    <Key outlineLocation={'r2-9'} animateIndex={26} keyText={['i']} />

    <Key outlineLocation={'r2-10'} animateIndex={9} keyText={['o']} />

    <Key outlineLocation={'r2-11'} animateIndex={7} keyText={['p']} />

    <Key outlineLocation={'r2-12'} animateIndex={14} keyText={['{', '[']} />

    <Key outlineLocation={'r2-13'} animateIndex={17} keyText={['}', ']']} />

    <Key outlineLocation={'r2-13'} animateIndex={17} keyText={['|', '\\']} />
  </KeyboardRowInner>
</KeyboardRow>
