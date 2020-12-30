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
      <Key cssClass={'key--fn'}>
        <KeyText text={'fn'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--control'}>
        <KeyText text={'control'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--option key--option--left'}>
        <KeyText text={'alt'}></KeyText>
        <KeyText text={'option'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--cmd key--cmd--left'}>
        <KeyText text={'⌘'}></KeyText>
        <KeyText text={'command'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--space'}></Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--cmd key--cmd--right'}>
      <KeyText text={'⌘'}></KeyText>
      <KeyText text={'command'}></KeyText>
      </Key>
    </KeyOutline>

    <KeyOutline>
      <Key cssClass={'key--option key--option--right'}>
        <KeyText text={'alt'}></KeyText>
        <KeyText text={'option'}></KeyText>
      </Key>
    </KeyOutline>

    <!-- add arrow keys here -->
  </KeyboardRowInner>
</KeyboardRow>
