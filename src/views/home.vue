<template>
  <h2>This is a home page</h2>
  <fancy-txt txt="Helo" />
</template>

<script>
import fancyTxt from '../components/fancy-txt.vue'

export default {
  name: 'home',
  components: {
    fancyTxt
  }
}
</script>

<style>
</style>