<script>
  import KeyboardRow from './KeyboardRow.svelte';
  import KeyboardRowInner from './KeyboardRowInner.svelte';
  import KeyOutline from './KeyOutline.svelte';
  import Key from './Key.svelte';
  import KeyText from './KeyText.svelte';
</script>

<KeyboardRow>
  <KeyboardRowInner>
      <Key cssClass={'key--fn'}>
        <KeyText text={'fn'}></KeyText>
      </Key>

      <Key cssClass={'key--control'}>
        <KeyText text={'control'}></KeyText>
      </Key>

      <Key cssClass={'key--option key--option--left'}>
        <KeyText text={'alt'}></KeyText>
        <KeyText text={'option'}></KeyText>
      </Key>

      <Key cssClass={'key--cmd key--cmd--left'}>
        <KeyText text={'⌘'}></KeyText>
        <KeyText text={'command'}></KeyText>
      </Key>

      <Key cssClass={'key--space'}></Key>

      <Key cssClass={'key--cmd key--cmd--right'}>
      <KeyText text={'⌘'}></KeyText>
      <KeyText text={'command'}></KeyText>
      </Key>

      <Key cssClass={'key--option key--option--right'}>
        <KeyText text={'alt'}></KeyText>
        <KeyText text={'option'}></KeyText>
      </Key>

    <!-- add arrow keys here -->
  </KeyboardRowInner>
</KeyboardRow>
