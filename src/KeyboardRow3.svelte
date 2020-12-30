<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <KeyOutline location={'r3-1'}>
      <Key cssClass={'key--capslock'}>
        <div class="dot"></div>
        <KeyText text={'caps lock'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-2'}>
      <Key>
        <KeyText text={'a'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-3'}>
      <Key animateIndex={10}>
        <KeyText text={'s'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-4'}>
      <Key animateIndex={22}>
        <KeyText text={'d'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-5'}>
      <Key animateIndex={29}>
        <KeyText text={'f'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-6'}>
      <Key animateIndex={27}>
        <KeyText text={'h'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-7'}>
      <Key animateIndex={23}>
        <KeyText text={'j'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-8'}>
      <Key animateIndex={24}>
        <KeyText text={'k'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-9'}>
      <Key animateIndex={32}>
        <KeyText text={'l'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-10'}>
      <Key animateIndex={11}>
        <KeyText text={':'}></KeyText>
        <KeyText text={';'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-11'}>
      <Key animateIndex={2}>
        <KeyText text={'"'}></KeyText>
        <KeyText text={"'"}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r3-12'}>
      <Key cssClass={'key--enter'}>
        <KeyText text={'enter'}></KeyText>
        <KeyText text={'return'}></KeyText>
      </Key>
    </KeyOutline>
  </KeyboardRowInner>
</KeyboardRow>
