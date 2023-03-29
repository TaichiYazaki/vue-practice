<template>
  <div id="app">
    <IfUsage />
    <ListUsage />
    <ComputedProperty />
  </div>
</template>

<script>
import IfUsage from './components/IfUsage.vue'
import ListUsage from './components/ListUsage.vue'
import ComputedProperty from './components/ComputedProperty.vue'
export default {
  name: 'App',
  components: {
    IfUsage
    , ListUsage
    , ComputedProperty
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
