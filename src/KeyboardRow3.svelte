<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineLocation={'r3-1'} cssClass={'key--capslock'} outlineCssClass={'key-outline--capslock'}>
      <div class="dot"></div>
      <KeyText text={'caps lock'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-2'}>
      <KeyText text={'a'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-3'} animateIndex={10}>
      <KeyText text={'s'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-4'} animateIndex={22}>
      <KeyText text={'d'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-5'} animateIndex={29}>
      <KeyText text={'f'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-6'} animateIndex={27}>
      <KeyText text={'g'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-7'} animateIndex={23}>
      <KeyText text={'h'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-8'} animateIndex={24}>
      <KeyText text={'j'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-9'} animateIndex={32}>
      <KeyText text={'k'}></KeyText>
    </Key>

    <Key outlineLocation={'r3-10'} animateIndex={6}>
      <KeyText text={'l'}></KeyText>
    </Key>

    <Key outlineLcation={'r3-11'} animateIndex={11}>
      <KeyText text={':'}></KeyText>
      <KeyText text={';'}></KeyText>
    </Key>

    <Key outlineLcation={'r3-11'} animateIndex={2}>
      <KeyText text={'"'}></KeyText>
      <KeyText text={"'"}></KeyText>
    </Key>

    <Key outlineLcation={'r3-12'} cssClass={'key--enter'} outlineCssClass={'key-outline--enter'}>
      <KeyText text={'enter'}></KeyText>
      <KeyText text={'return'}></KeyText>
    </Key>
  </KeyboardRowInner>
</KeyboardRow>
