<template>
  <svg
    :class="['icon', `icon-${name}`]"
    :width="width"
    :height="height"
    :viewBox="`0 0 ${width} ${height}`"
    preserveAspectRatio="xMidYMid meet"
  >
    <use :href="`#icon-${name}`" />
  </svg>
</template>

<script>
export default {
  name: 'SVGIcon',
  props: {
    name: {
      type: String,
      required: true
    },
    width: {
      type: [String, Number],
      required: false,
      default: 24
    },
    height: {
      type: [String, Number],
      required: false,
      default: 24
    }
  }
}
</script>
