<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';

  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key outlineLocation={'r4-1'} cssClass={'key--shift key--shift--left'} outlineCssClass={'key-outline--shift'}>
      <KeyText text={'shift'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-2'} animateIndex={12}>
      <KeyText text={'z'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-3'} animateIndex={3}>
      <KeyText text={'x'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-4'} animateIndex={25}>
      <KeyText text={'c'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-5'} animateIndex={33}>
      <KeyText text={'v'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-6'} animateIndex={4}>
      <KeyText text={'b'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-7'} animateIndex={5}>
      <KeyText text={'n'}></KeyText>
    </Key>

    <Key outLinelocation={''}>
      <KeyText text={'m'}></KeyText>
    </Key>

    <Key outlineLocation={'r4-8'} animateIndex={19}>
      <KeyText text={'<'}></KeyText>
      <KeyText text={','}></KeyText>
    </Key>

    <Key outlineLocation={'r4-9'} animateIndex={21}>
      <KeyText text={'>'}></KeyText>
      <KeyText text={'.'}></KeyText>
    </Key>

    <Key outlinelLcation={'r4-10'} animateIndex={13}>
      <KeyText text={'?'}></KeyText>
      <KeyText text={'/'}></KeyText>
    </Key>

    <Key outlinelLcation={'r4-11'} cssClass={'key--shift key--shift--right'} outlineCssClass={'key-outline--shift'}>
      <KeyText text={'shift'}></KeyText>
    </Key>
  </KeyboardRowInner>
</KeyboardRow>
