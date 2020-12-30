<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow cssClass={''}>
  <KeyboardRowInner cssClass={''}>
    <KeyOutline location={'r2-1'}>
      <Key cssClass={'key--tab'}>
        <KeyText text={'tab'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-2'}>
      <Key cssClass={''} animateIndex={1}>
        <KeyText text={'q'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-3'}>
      <Key cssClass={''} animateIndex={18}>
        <KeyText text={'w'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-4'}>
      <Key cssClass={''} animateIndex={20}>
        <KeyText text={'e'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-5'}>
      <Key cssClass={''} animateIndex={8}>
        <KeyText text={'r'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-6'}>
      <Key cssClass={''} animateIndex={31}>
        <KeyText text={'t'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-7'}>
      <Key cssClass={''} animateIndex={30}>
        <KeyText text={'y'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-8'}>
      <Key cssClass={''} animateIndex={28}>
        <KeyText text={'u'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-9'}>
      <Key cssClass={''} animateIndex={26}>
        <KeyText text={'i'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-10'}>
      <Key cssClass={''} animateIndex={9}>
        <KeyText text={'o'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-11'}>
      <Key cssClass={''} animateIndex={7}>
        <KeyText text={'p'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-12'}>
      <Key cssClass={''} animateIndex={14}>
        <KeyText text={'{'}></KeyText>
        <KeyText text={'['}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r2-13'}>
      <Key cssClass={'}'} animateIndex={17}>
        <KeyText text={']'}></KeyText>
      </Key>
    </KeyOutline>
  </KeyboardRowInner>
</KeyboardRow>
