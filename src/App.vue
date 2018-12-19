<template>
  <div id="app">
    <router-view/>
    <appheader></appheader>
  </div>
</template>

<script >
import Header from './components/header'
export default {
  name: 'App',
  components: {
    'appheader': Header
  }
}
</script>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
