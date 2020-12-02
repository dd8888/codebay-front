<template>
  <div>
    <Navbar />
    <Title />
    <Header />
    <Images class="images" />
    <Bottom />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Title from "./components/Title.vue";
import Header from "./components/Header.vue";
import Images from "./components/Images.vue";
import Bottom from "./components/Bottom.vue";
import Footer from "./components/Footer";

export default {
  name: "App",
  components: {
    Navbar,
    Title,
    Header,
    Images,
    Bottom,
    Footer
  }
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap");

div {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
