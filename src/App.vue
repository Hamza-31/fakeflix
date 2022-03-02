<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo_flix.svg" />
    <MainHeader />
    <SearchResults />
  </div>
</template>

<script>
import MainHeader from "./components/MainHeader.vue";
import SearchResults from "./components/SearchResults.vue";
import "./style.css";

export default {
  name: "App",
  components: {
    MainHeader,
    SearchResults,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: white;

  width: 1100px;
  margin: 0 auto;
}
img {
  width: 50%;
}
</style>
