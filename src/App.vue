<template>
  <HeaderPrime />
  <MainPrime />
  <FooterPrime />
</template>

<script>
import HeaderPrime from "./components/HeaderPrime.vue";
import MainPrime from "./components/MainPrime.vue";
import FooterPrime from "./components/FooterPrime.vue";

export default {
  name: "App",
  components: {
    HeaderPrime,
    MainPrime,
    FooterPrime,
  },
};
</script>

<style>
body {
  height: 100vh;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  height: 100%;
}
</style>
