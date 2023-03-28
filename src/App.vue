<template>
  <div id="app">
    <IfUsage />
    <ListUsage />
  </div>
</template>

<script>
import IfUsage from './components/IfUsage.vue'
import ListUsage from './components/ListUsage.vue'
export default {
  name: 'App',
  components: {
    IfUsage
    , ListUsage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
