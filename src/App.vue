<template>
  <div id="app">
    <Footer />
  </div>
</template>

<script>
import Footer from "./components/FooterComponent.vue";

export default {
  name: "App",
  components: {
    Footer,
  },
};
</script>

<style>
#app {
  background-color: #333;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
