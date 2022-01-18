<template>
  <div id="app">
    <Header />
    <main>
    <Services />
    <About />

    </main>
    <Footer />
  </div>
</template>

<script>

import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Services from "./components/Services.vue";
import About from "./components/About.vue";




export default {
  name: "App",
  components: {
   Header,
   Footer,
   Services,
   About,
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
