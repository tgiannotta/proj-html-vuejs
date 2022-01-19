<template>
  <div id="app">

    <Header />
    <main>
    <Services />
    <About />
    <Portfolio />
    <PriceList />
    <Blog />
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
import Blog from "./components/Blog.vue";







export default {
  name: "App",
  components: {
   Header,
   Footer,
   Services,
   About,
   Portfolio,
   PriceList,
   Blog,
  },
};
</script>

<style lang="scss">
@import "./style/general.scss";
#app {

  main{

    height: 8000px;
  }
}
</style>
