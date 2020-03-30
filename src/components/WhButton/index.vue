<template>
  <button class="wh-button">
    <svg class="icon" aria-hidden="true">
      <use xlink:href="#wh-icon-arrow-lift"></use>
    </svg>
    {{ text }}
  </button>
</template>

<script>
export default {
  name: 'WhButton',
  props: {
    text: {
      type: String,
      default: ''
    },
    icon: {
      type: String,
      default: ''
    }
  },
  data() {
    return {}
  }
}
</script>

<style lang="scss">
  .wh-button {
    padding: 0 $--wh-button-padding;
    height: $--wh-button-height;
    font-size: 14px;
    border-radius: 4px;
    color: $--wh-accent-color-1;
    border: solid 1px $--wh-accent-color-2;
    background-color: white;
    cursor: pointer;

    &:hover {
      background-color: $--wh-accent-color-3;
    }
    &:focus {
      border-color: $--wh-accent-color-1;
      outline: none;
    }
  }
</style>
