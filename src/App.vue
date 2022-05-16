<template>
  <div id="app">
    <AppTitle />
    <AppImage />
  </div>
</template>

<script>
import AppTitle from "./components/AppTitle.vue";
import AppImage from "./components/AppImage.vue";
export default {
  name: "App",
  components: {
    AppTitle,
    AppImage,
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
