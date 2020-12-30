<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <KeyOutline location={'r4-1'}>
      <Key cssClass={'key--shift key--shift--left'}>
        <KeyText text={'shift'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-2'}>
      <Key animateIndex={12}>
        <KeyText text={'z'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-3'}>
      <Key animateIndex={3}>
        <KeyText text={'x'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-4'}>
      <Key animateIndex={25}>
        <KeyText text={'c'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-5'}>
      <Key animateIndex={33}>
        <KeyText text={'v'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-6'}>
      <Key animateIndex={4}>
        <KeyText text={'b'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-7'}>
      <Key animateIndex={5}>
        <KeyText text={'n'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={''}>
      <Key>
        <KeyText text={'m'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-8'}>
      <Key animateIndex={19}>
        <KeyText text={'<'}></KeyText>
        <KeyText text={','}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-9'}>
      <Key animateIndex={21}>
        <KeyText text={'>'}></KeyText>
        <KeyText text={'.'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-10'}>
      <Key animateIndex={13}>
        <KeyText text={'?'}></KeyText>
        <KeyText text={'/'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r4-11'}>
      <Key cssClass={'key--shift key--shift--right'}>
        <KeyText text={'shift'}></KeyText>
      </Key>
    </KeyOutline>
  </KeyboardRowInner>
</KeyboardRow>
