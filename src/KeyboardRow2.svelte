<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineLocation={'r2-1'} cssClass={'key--tab'} outlineCssClass={`key-outline--tab`}>
      <KeyText text={'tab'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-2'} animateIndex={1}>
      <KeyText text={'q'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-3'} animateIndex={18}>
      <KeyText text={'w'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-4'} animateIndex={20}>
      <KeyText text={'e'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-5'} animateIndex={8}>
      <KeyText text={'r'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-6'} animateIndex={31}>
      <KeyText text={'t'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-7'} animateIndex={30}>
      <KeyText text={'y'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-8'} animateIndex={28}>
      <KeyText text={'u'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-9'} animateIndex={26}>
      <KeyText text={'i'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-10'} animateIndex={9}>
      <KeyText text={'o'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-11'} animateIndex={7}>
      <KeyText text={'p'}></KeyText>
    </Key>

      <Key outlineLocation={'r2-12'} animateIndex={14}>
      <KeyText text={'{'}></KeyText>
      <KeyText text={'['}></KeyText>
    </Key>

    <Key outlineLocation={'r2-13'} animateIndex={17}>
      <KeyText text={'}'}></KeyText>
      <KeyText text={']'}></KeyText>
    </Key>

    <Key outlineLocation={'r2-13'} animateIndex={17}>
      <KeyText text={'|'}></KeyText>
      <KeyText text={'\\'}></KeyText>
    </Key>
  </KeyboardRowInner>
</KeyboardRow>
