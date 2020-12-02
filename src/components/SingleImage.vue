<template>
  <div class="p-1">
    <mdb-card class="mb-3">
      <mdb-view hover cascade fluid>
        <a href="#!">
          <mdb-card-image
            class="p-xs-1 p-sm-3 p-lg-5 img-fluid"
            :src="src"
            alt="Card image cap"
            v-animateOnScroll="{
              animation: 'fadeIn'
            }"
          ></mdb-card-image>
          <mdb-mask flex-center waves overlay="white-slight"></mdb-mask>
        </a>
      </mdb-view>
      <mdb-card-body class="text-center" cascade>
        <mdb-card-title><strong>Item title</strong></mdb-card-title>
        <mdb-card-text>Item category</mdb-card-text>
        <p class="h5">${{ Math.floor(Math.random() * (200 - 1) + 1) }}.00</p>
      </mdb-card-body>
    </mdb-card>
  </div>
</template>

<script>
import {
  animateOnScroll,
  mdbCard,
  mdbCardImage,
  mdbCardBody,
  mdbCardTitle,
  mdbCardText,
  mdbView,
  mdbMask
} from "mdbvue";
export default {
  name: "SingleImage",
  props: {
    src: String
  },
  directives: {
    animateOnScroll
  },
  components: {
    mdbCard,
    mdbCardImage,
    mdbCardBody,
    mdbCardTitle,
    mdbCardText,
    mdbView,
    mdbMask
  }
};
</script>

<style></style>
