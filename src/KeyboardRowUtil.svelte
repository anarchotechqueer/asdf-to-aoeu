<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow cssClass={'keyboard-row--util'}>
  <KeyboardRowInner>
    <Key cssClass={'key--util key--esc'} outlineCssClass={'key-outline--util'} keyText={['esc']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f1']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f2']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f3']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f4']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f5']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f6']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f7']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f8']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f9']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f10']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f11']} />

    <Key cssClass={'key--util key--f'} outlineCssClass={'key-outline--util'} keyText={['f12']} />

    <Key cssClass={'key--util key--f key--power'} outlineCssClass={'key-outline--util'} keyText={['⏻']} />
  </KeyboardRowInner>
</KeyboardRow>
