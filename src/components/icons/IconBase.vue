<template>
  <svg :width="width" :height="height" :aria-labelledby="iconName" role="presentation">
    <slot></slot>
  </svg>
</template>

<script>
export default {
  name: 'iconBase',
  props: {
    iconName: {
      type: String,
      default: 'circle'
    },
    width: {
      type: [Number, String],
      default: '44'
    },
    height: {
      type: [Number, String],
      default: '44'
    },
  }
}
</script>

<style scoped>
svg {
  display: inline-block;
  vertical-align: baseline;
  margin-bottom: -2px; /* yes, I'm that particular about formatting */
}
</style>
