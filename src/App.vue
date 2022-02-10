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
  font-family: 'Roboto', sans-serif;
}

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700;900&display=swap');


#app {
  font-family: sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: black;
}
.container{
  display: flex;
  // justify-content: center;
  width: 1200px;
  margin: 0 auto;


}
</style>
