<template>
  <div id="app">

    <Header />
    <main>
    <Services />
    <About />
    <Portfolio />
    <PriceList />
    </main>
    <Footer />
  </div>
</template>

<script>

import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Services from "./components/Services.vue";
import About from "./components/About.vue";
import Portfolio from "./components/Portfolio.vue";
import PriceList from "./components/PriceList.vue";






export default {
  name: "App",
  components: {
   Header,
   Footer,
   Services,
   About,
   Portfolio,
   PriceList,
  },
};
</script>

<style lang="scss">
@import "./style/general.scss";
#app {

  main{
    height: 4000px;
    background-color: orange;
  }
}
</style>
