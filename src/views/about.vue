<template>
  <h2>This is an about page</h2>
  <custom-btn>{{ msg }}</custom-btn>
</template>

<script>
import customBtn from '../components/custom-btn.vue'

export default {
  name: 'about',
  components: {
    customBtn
  },
  data() {
    return {
      msg: 'Dont click me'
    }
  }
}
</script>

<style>
</style>