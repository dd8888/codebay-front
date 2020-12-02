<template>
  <div>
    <Navbar />
    <Title />
    <Header />
    <Images />
    <Bottom />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Title from "./components/Title.vue";
import Header from "./components/Header.vue";
import Images from "./components/Images.vue";
import Bottom from "./components/Bottom.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Title,
    Header,
    Images,
    Bottom
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap");

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
