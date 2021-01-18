<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow cssClass={'keyboard-row--util'}>
  <KeyboardRowInner>
    <Key cssClass={'key--util key--esc'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'esc'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f1'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f2'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f3'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f4'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f5'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f6'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f7'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f8'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f9'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f10'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f11'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'f12'}></KeyText>
    </Key>

    <Key cssClass={'key--util key--f key--power'} outlineCssClass={'key-outline--util'}>
      <KeyText text={'&#x23FB;'}></KeyText>
    </Key>
  </KeyboardRowInner>
</KeyboardRow>
