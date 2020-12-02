<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <mdb-dropdown class="mt-2">
            <mdb-dropdown-toggle
              slot="toggle"
              size="xs"
              style="color: white;  
            text-shadow: 0 0 0 white;"
              ><span class="numberCircle mr-2">4</span> 🛒</mdb-dropdown-toggle
            >
            <mdb-dropdown-menu>
              <mdb-dropdown-item>Item 1</mdb-dropdown-item>
              <mdb-dropdown-item>Item 2</mdb-dropdown-item>
              <mdb-dropdown-item>Item 3</mdb-dropdown-item>
              <mdb-dropdown-item>Item 4</mdb-dropdown-item>
            </mdb-dropdown-menu>
          </mdb-dropdown>

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
import {
  mdbDropdown,
  mdbDropdownItem,
  mdbDropdownMenu,
  mdbDropdownToggle
} from "mdbvue";
export default {
  name: "HelloWorld",
  components: {
    mdbDropdown,
    mdbDropdownItem,
    mdbDropdownMenu,
    mdbDropdownToggle
  }
};
</script>

<style scoped>
.numberCircle {
  padding: 10px;
  position: relative;
  background: rgb(235, 162, 5);
  color: white;
  text-align: center;

  font: 14px Arial, sans-serif;
}
</style>
