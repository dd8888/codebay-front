<template>
  <div
    style="display: flex;
    flex-wrap: wrap;
    justify-content: space-around;"
  >
    <SingleImage src="https://picsum.photos/150/200/?image=1" />
    <SingleImage src="https://picsum.photos/150/200/?image=2" />
    <SingleImage src="https://picsum.photos/150/200/?image=3" />
    <SingleImage src="https://picsum.photos/150/200/?image=4" />
  </div>
</template>

<script>
import SingleImage from "./SingleImage";
export default {
  name: "Images",
  components: {
    SingleImage
  }
};
</script>

<style></style>
