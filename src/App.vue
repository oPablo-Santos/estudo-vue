<template>
  <h1>Hello world</h1>
  <LifeCycle />
  <Info/>
  <Picture />
</template>

<script>
import LifeCycle from "./components/LifeCycle.vue";
import Picture from "./components/Picture.vue";
import Info from "./components/Info.vue";

export default {
  name: "App",
  components: {
    LifeCycle,
    Picture,
    Info
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
