<template>
  <h1>Hello, i'm App.vue</h1>
  {{ msg }}
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      msg: 'Hello Vite + Vue3!'
    }
  }
}
</script>