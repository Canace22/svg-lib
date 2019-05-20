<template>
  <g>
    <circle cx="30" cy="50" :r="r" class="styleC"></circle>
    <circle cx="60" cy="50" :r="r" class="styleC"></circle>
    <circle cx="90" cy="50" :r="r" class="styleC"></circle>
  </g>
</template>
<script>
export default {
  name: 'circle',
  props: {
    r: {
      type: String,
      default: '25'
    },
  }
}
</script>

<style lang="scss" scoped>
.styleC {
  fill: none;
  stroke: rgb(102, 100, 100);
  stroke-width: 1pt;
  &:hover {
    fill: rgb(102, 100, 100);
    stroke: #fff;
    cursor: pointer;
  }
}
</style>
