<template>
  <div id="app">
    <IfUsage />
    <ListUsage />
    <ComputedProperty />
    <ComputedProperty2 />
    <LifeCycle />
    <WatchVue />
  </div>
</template>

<script>
import IfUsage from "./components/IfUsage.vue";
import ListUsage from "./components/ListUsage.vue";
import ComputedProperty from "./components/ComputedProperty.vue";
import LifeCycle from "./components/LifeCycle.vue";
import WatchVue from "./components/WatchVue.vue";
export default {
  name: "App",
  components: {
    IfUsage,
    ListUsage,
    ComputedProperty,
    LifeCycle,
    WatchVue,
  },
};
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
