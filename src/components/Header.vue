<template>
  <div class="mt-2 p-3">
    <b-carousel
      id="carousel-fade"
      controls
      style="text-shadow: 0px 0px 2px #000"
      fade
      indicators
      class="img-fluid d-none d-sm-block"
    >
      <b-carousel-slide
        img-src="https://picsum.photos/1024/580/?image=41"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://picsum.photos/1024/580/?image=42"
      ></b-carousel-slide>
      <b-carousel-slide
        img-src="https://picsum.photos/1024/580/?image=43"
      ></b-carousel-slide>
    </b-carousel>
    <p class="h5 mt-3">Intro copy headline</p>
    <p>
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum enim
      mi, pretium ac enim vitae, malesuada tristique velit. In hac habitasse
      platea dictumst. Mauris interdum eros elit, non vulputate nunc varius eu.
      Nunc cursus risus nisi, sed tristique orci finibus eget. Ut sollicitudin
      ex a urna euismod aliquet. Pellentesque egestas sem risus, non rutrum enim
      hendrerit in. Aliquam consequat, nunc et porta consequat, nunc nisi
      aliquet mauris, eu hendrerit tortor mi eu turpis.
    </p>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style></style>
