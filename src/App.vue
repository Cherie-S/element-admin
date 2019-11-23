<template>
  <div id="app">
    <login></login>
  </div>
</template>

<script>
  import Login from '@/components/login'
  export default {
    name: 'App',
    components: {
      'login': Login
    }
  }
</script>

<style>
  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    /*color: #2c3e50;*/
    height: 100%;
  }
</style>
