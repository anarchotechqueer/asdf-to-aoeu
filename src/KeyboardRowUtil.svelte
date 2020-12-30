<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow cssClass={'keyboard-row--util'}>
  <KeyboardRowInner>
    <KeyOutline>
      <Key cssClass={'key--util key--esc'}>
        <KeyText text={'esc'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f1'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f2'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f3'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f4'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f5'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f6'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f7'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f8'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f9'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f10'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f11'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f'}>
        <KeyText text={'f12'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--util key--f key--power'}>
        <KeyText text={'&#x23FB;'}></KeyText>
      </Key>
    </KeyOutline>
  </KeyboardRowInner>
</KeyboardRow>
