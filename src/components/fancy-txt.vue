<template>
  <h3>Fancy Txt</h3>
  {{ txt }}
  {{ num }}
</template>

<script>

export default {
  name: 'fancy-txt',
  props: {
    txt: {
      type: String,
      required: true,
      default: () => ({ name: 'Puki' }),
      validator: (value) => value.length > 4
    },
    num: Number
  },
}
</script>

<style>
</style>