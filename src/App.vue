<template>
  <div id="app">
    <Header />
    <main>
      <h2>Prova main</h2>
    </main>
    <Footer />
  </div>
</template>

<script>

import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";


export default {
  name: "App",
  components: {
   Header,
   Footer,
  },
};
</script>

<style lang="scss">
@import "./style/general.scss";
#app {

  main{
    height: 2000px;
    background-color: orange;
  }
}
</style>
