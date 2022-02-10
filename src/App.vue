<template>
  <div id="app">
    <Header />
    <Main />
    <CTA />
    <Footer />

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import CTA from "./components/CTA.vue";
import Footer from "./components/Footer.vue";




export default {
  name: "App",
  components: {
  Header,
  Main,
  CTA,
  Footer,
  },
};
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: black;

}
</style>
