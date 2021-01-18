<script>
	export let cssClass = '';
	export let outlineCssClass = '';
	export let animateIndex = '';
	export let keyText = [];
</script>

<style type="text/scss">
 @import './mixins.scss';
 .key-outline {
   width: var(--key-outline-size);
   height: var(--key-outline-size);
   border-radius: 1.7mm;
   border: var(--key-outline-border-size) solid var(--color-black);
   flex-grow: 0;
   flex-shrink: 0;

   &:not(:first-child) {
     margin-left: var(--gap-size);
   }

	 &--util {
		 height: auto;
		 flex-grow: 1;

		 .key {
			 width: 100%;
		 }
	 }

	 &--delete {
     @include action-key;
     flex-grow: 1;
     justify-content: flex-end;
     align-items: flex-end;
   }

	 &--tab {
     @include action-key;
     justify-content: flex-end;
     align-items: flex-start;
     flex-grow: 1;
   }

   &--capslock {
     @include action-key;
     justify-content: space-between;
     align-items: flex-start;

     .dot {
       width: 4px;
       height: 4px;
       background-color: white;
       border-radius: 50%;
       flex-shrink: 0;
     }
   }

   &--enter {
     @include action-key;
     justify-content: space-between;
     align-items: flex-end;
   }

   &--shift {
     @include action-key;
     justify-content: flex-end;

     &--left {
       align-items: flex-start;
     }

     &--right {
       align-items: flex-end;
     }
   }

	 &.key--fn {
		 @include action-key;
		 justify-content: flex-end;
		 align-items: flex-start;
		 width: 15.4mm;
	 }

	 &--control {
		 @include action-key;
		 justify-content: flex-end;
		 align-items: flex-start;
		 width: 16.4mm;
	 }

	 &--option {
		 @include action-key;
		 justify-content: space-between;
		 width: 16.4mm;

		 &--left {
			 align-items: flex-start;
		 }

		 &--right {
			 align-items: flex-end;
		 }
	 }

	 &--cmd {
		 @include action-key;
		 justify-content: space-between;
		 width: 21mm;

		 .key-text {
			 &:first-child {
				 font-size: var(--small-font-size);
			 }
		 }
		 &--left {
			 align-items: flex-end;
		 }

		 &--right {
			 align-items: flex-start;
		 }
	 }
 }

.key {
  text-transform: uppercase;
  color: white;
  background-color: var(--color-black);
  padding: 8px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  width: var(--key-size);
  height: var(--key-size);
  border-radius: 1.7mm;
  flex-shrink: 0;
  flex-grow: 0;
  transition-duration: .25s;
  transition-property: transform, box-shadow;

  &:not(:first-child) {
    margin-left: var(--gap-size);
  }

  &--util {
    font-size: var(--mini-font-size);
    padding: 5px;
  }

  &--f {
    justify-content: flex-end;
    align-items: flex-end;
  }

  &--power {
    justify-content: center;
    align-items: center;
    font-size: 16px;
  }

  &--esc {
    text-transform: lowercase;
    font-size: var(--small-font-size);
  }



  &--util {
    height: var(--key-size-util-height);
    flex-grow: 1;
  }


  &--space {
    width: var(--key-size-space);
    flex-shrink: 0;
  }

  &--arrow {
    width: 16.5mm;
    height: 7.5mm;

    &--horizontal {
      margin-top: auto;
    }

    &--right {
      &:before {
        transform: rotate(180deg)
      }
    }

    &--up {
      &:before {
        transform: rotate(90deg)
      }
    }

    &--down {
      &:before {
        transform: rotate(-90deg)
      }
    }

    &:before {
      content: "";
      display: block;
      width: 0px;
      height: 0px;
      border-top: 4px solid transparent;
      border-bottom: 4px solid transparent;
      border-right: 8px solid white;
    }
  }

  &--selected {
    transform: scale(1.05);
    position: relative;
    z-index: 1;
    box-shadow: 3px 3px 0px 0px rgba(0,0,0,.23);
  }

  &--active {
    transition-duration: 0;
  }
}

.key-text {
  line-height: 1.2;

  &:not(:first-child) {
    margin-top: 5px;
  }
}
</style>

<div class={`key-outline ${outlineCssClass}`}>
	<div class={`key ${cssClass}`} data-animate={animateIndex}>
		{#each keyText as t}
			<div class="key-text">{t}</div>
		{/each}
		<slot></slot>
	</div>
</div>
