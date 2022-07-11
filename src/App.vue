<template>
  <h1>Hello, i'm App.vue</h1>
  <nav>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
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