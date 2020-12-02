<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item-dropdown
            text="🛒"
            left
            class="p-2"
            style="color: transparent;  
            text-shadow: 0 0 0 white;"
          >
            <b-dropdown-item href="#">Shopping Item 1</b-dropdown-item>
            <b-dropdown-item href="#">Shopping Item 2</b-dropdown-item>
            <b-dropdown-item href="#">Shopping Item 3</b-dropdown-item>
            <b-dropdown-item href="#">Shopping Item 4</b-dropdown-item>
          </b-nav-item-dropdown>
          <b-navbar-nav class="p-2">
            <b-nav-item href="#">Profile</b-nav-item>
          </b-navbar-nav>
          <b-nav-form class="p-2">
            <b-form-input
              size="sm"
              class="mr-sm-2 mt-1"
              placeholder="Search"
            ></b-form-input>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>

<style scoped></style>
