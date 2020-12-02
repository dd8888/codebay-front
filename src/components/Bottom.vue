<template>
  <div class="mt-2 p-3 d-md-flex wrapper">
    <div class="d-lg-none col col-xs-2 mb-4">
      <h6>Quick Links</h6>
      <div>
        <span class="fa fa-home" aria-hidden="true"></span><a href="#"> Home</a>
      </div>
      <div>
        <span class="fa fa-calendar" aria-hidden="true"></span
        ><a href="#"> Event</a>
      </div>
      <div>
        <span class="fa fa-life-ring" aria-hidden="true"></span
        ><a href="#"> Support</a>
      </div>
      <div>
        <span class="fa fa-id-card" aria-hidden="true"></span
        ><a href="#"> Contact</a>
      </div>
    </div>
    <div class="col mb-4">
      <h6>Announcements / Promoted Content</h6>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum enim
        mi, pretium ac enim vitae, malesuada tristique velit. In hac habitasse
        platea dictumst.
      </p>
    </div>
    <div class="col" style="text-align: center">
      <h6>Coming soon</h6>
      <img
        src="https://picsum.photos/450/350/?image=5"
        alt="Coming soon"
        class="img-fluid img-thumbnail"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Bottom"
};
</script>

<style scoped>
.wrapper {
  background-color: rgb(216, 216, 216);
}
a {
  color: black;
}
</style>
