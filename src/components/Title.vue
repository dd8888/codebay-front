<template>
  <div>
    <b-navbar
      style="display: flex;
    justify-content: space-between;"
      class="mt-2 p-3"
    >
      <h2>A big title</h2>
      <div class="d-block d-sm-none">
        <mdb-dropdown class="mb-1">
          <mdb-dropdown-toggle slot="toggle" color="dark" size="sm"
            >Navigation</mdb-dropdown-toggle
          >
          <mdb-dropdown-menu>
            <mdb-dropdown-item>Home</mdb-dropdown-item>
            <mdb-dropdown-item>Event</mdb-dropdown-item>
            <mdb-dropdown-item>Support</mdb-dropdown-item>
            <mdb-dropdown-item>Contact</mdb-dropdown-item>
          </mdb-dropdown-menu>
        </mdb-dropdown>
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
import {
  mdbDropdown,
  mdbDropdownItem,
  mdbDropdownMenu,
  mdbDropdownToggle
} from "mdbvue";
export default {
  name: "Title",
  components: {
    mdbDropdown,
    mdbDropdownItem,
    mdbDropdownMenu,
    mdbDropdownToggle
  }
};
</script>

<style></style>
