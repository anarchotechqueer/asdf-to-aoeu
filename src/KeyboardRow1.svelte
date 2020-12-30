<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <KeyOutline>
      <Key>
        <KeyText text={'~'}></KeyText>
        <KeyText text={'`'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'!'}></KeyText>
        <KeyText text={'1'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'@'}></KeyText>
        <KeyText text={'2'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'#'}></KeyText>
        <KeyText text={'3'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'$'}></KeyText>
        <KeyText text={'4'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'%'}></KeyText>
        <KeyText text={'5'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'^'}></KeyText>
        <KeyText text={'6'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'&'}></KeyText>
        <KeyText text={'7'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'*'}></KeyText>
        <KeyText text={'8'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={'('}></KeyText>
        <KeyText text={'9'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key>
        <KeyText text={')'}></KeyText>
        <KeyText text={'0'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r1-12'}>
      <Key animateIndex={15}>
        <KeyText text={'_'}></KeyText>
        <KeyText text={'-'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline location={'r1-13'}>
      <Key animateIndex={16}>
        <KeyText text={'+'}></KeyText>
        <KeyText text={'='}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--delete'}>
        <KeyText text={'delete'}></KeyText>
      </Key>
    </KeyOutline>
  </KeyboardRowInner>
</KeyboardRow>
