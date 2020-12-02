<template>
  <div class="p-1">
    <b-img
      :src="src"
      fluid
      alt="Featured image"
      v-animateOnScroll="{
        animation: 'bounceInLeft',
        delay: 300,
        position: 20
      }"
    ></b-img>
    <p class="h4 mt-3">Item title</p>
    <p class="h5">Item category</p>
    <p class="h5">${{ Math.floor(Math.random() * (200 - 1) + 1) }}.00</p>
  </div>
</template>

<script>
export default {
  name: "SingleImage",
  props: {
    src: String
  }
};
</script>

<style></style>
