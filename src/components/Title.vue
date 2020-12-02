<template>
  <div>
    <b-navbar
      style="display: flex;
    justify-content: space-between;"
      class="mt-2 p-3"
    >
      <h2>A big title</h2>
      <div class="d-block d-sm-none dropleft">
        <b-dropdown id="dropdown-1" text="Home" class="m-md-2 w-25">
          <b-dropdown-item>Home</b-dropdown-item>
          <b-dropdown-item>Event</b-dropdown-item>
          <b-dropdown-item>Support</b-dropdown-item>
          <b-dropdown-item>Contact</b-dropdown-item>
        </b-dropdown>
      </div>
      <b-navbar-nav class="ml-auto d-none d-sm-block">
        <b-navbar-nav>
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">Event</b-nav-item>
          <b-nav-item href="#">Accesories</b-nav-item>
          <b-nav-item href="#">Apparel</b-nav-item>
          <b-nav-item href="#">Featured Items</b-nav-item>
        </b-navbar-nav>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Title"
};
</script>

<style></style>
