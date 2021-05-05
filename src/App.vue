<template>
  <div id="app">
    <!-- <Navbar /> -->
    <Tile />
  </div>
</template>

<script>
// import Navbar from "./components/Navbar.vue";
import Tile from "./components/Tile.vue";
export default {
  name: "App",
  components: {
    // Navbar,
    Tile
  },
  //data is similar to react state
  data() {
    return {
      letters: ["A", "B", "C"]
    };
  }
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
