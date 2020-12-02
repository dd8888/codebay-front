<template>
  <div>
    <Navbar />
    <Title />
    <Header />
    <Images />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Title from "./components/Title.vue";
import Header from "./components/Header.vue";
import Images from "./components/Images.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Title,
    Header,
    Images
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
