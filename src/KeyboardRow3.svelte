<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineLocation={'r3-1'} cssClass={'key--capslock'} outlineCssClass={'key-outline--capslock'} keyText={['caps lock']}>
      <div class="dot"></div>
    </Key>

    <Key outlineLocation={'r3-2'} keyText={['a']} />

    <Key outlineLocation={'r3-3'} animateIndex={10} keyText={['s']} />

    <Key outlineLocation={'r3-4'} animateIndex={22} keyText={['d']} />

    <Key outlineLocation={'r3-5'} animateIndex={29} keyText={['f']} />

    <Key outlineLocation={'r3-6'} animateIndex={27} keyText={['g']} />

    <Key outlineLocation={'r3-7'} animateIndex={23} keyText={['h']} />

    <Key outlineLocation={'r3-8'} animateIndex={24} keyText={['j']} />

    <Key outlineLocation={'r3-9'} animateIndex={32} keyText={['k']} />

    <Key outlineLocation={'r3-10'} animateIndex={6} keyText={['l']} />

    <Key outlineLcation={'r3-11'} animateIndex={11} keyText={[':', ';']} />

    <Key outlineLcation={'r3-11'} animateIndex={2} keyText={['"', "'"]} />

    <Key outlineLcation={'r3-12'} cssClass={'key--enter'} outlineCssClass={'key-outline--enter'} keyText={['enter', 'return']} />
  </KeyboardRowInner>
</KeyboardRow>
