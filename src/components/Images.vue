<template>
  <mdb-card-group deck>
    <SingleImage src="https://picsum.photos/150/200/?image=1" />
    <SingleImage src="https://picsum.photos/150/200/?image=2" />
    <SingleImage src="https://picsum.photos/150/200/?image=3" />
    <SingleImage src="https://picsum.photos/150/200/?image=4" />
  </mdb-card-group>
</template>

<script>
import SingleImage from "./SingleImage";
import { mdbCardGroup } from "mdbvue";
export default {
  name: "Images",
  components: {
    SingleImage,
    mdbCardGroup
  }
};
</script>

<style scoped>
div {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
</style>
