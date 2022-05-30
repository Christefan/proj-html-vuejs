<template>
  <div id="app">
    <AppHeader />
    <AppMain />
  </div>
</template>

<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
export default {
  name: "App",
  components: {
    AppHeader,
    AppMain,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
