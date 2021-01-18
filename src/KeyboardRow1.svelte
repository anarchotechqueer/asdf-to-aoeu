<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
    <Key>
      <KeyText text={'~'}></KeyText>
      <KeyText text={'`'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'!'}></KeyText>
      <KeyText text={'1'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'@'}></KeyText>
      <KeyText text={'2'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'#'}></KeyText>
      <KeyText text={'3'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'$'}></KeyText>
      <KeyText text={'4'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'%'}></KeyText>
      <KeyText text={'5'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'^'}></KeyText>
      <KeyText text={'6'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'&'}></KeyText>
      <KeyText text={'7'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'*'}></KeyText>
      <KeyText text={'8'}></KeyText>
    </Key>

    <Key>
      <KeyText text={'('}></KeyText>
      <KeyText text={'9'}></KeyText>
    </Key>

    <Key>
      <KeyText text={')'}></KeyText>
      <KeyText text={'0'}></KeyText>
    </Key>

    <Key outlineLocation={'r1-12'} animateIndex={15}>
      <KeyText text={'_'}></KeyText>
      <KeyText text={'-'}></KeyText>
    </Key>

    <Key outlineLocation={'r1-13'} animateIndex={16}>
      <KeyText text={'+'}></KeyText>
      <KeyText text={'='}></KeyText>
    </Key>

    <Key cssClass={'key--delete'} outlineCssClass={'key-outline--delete'}>
      <KeyText text={'delete'}></KeyText>
    </Key>
  </KeyboardRowInner>
</KeyboardRow>
