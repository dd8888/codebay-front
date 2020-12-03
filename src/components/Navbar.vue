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
              ><span class="badge badge-danger mr-2">4</span>
              <i class="fas fa-shopping-cart"></i
            ></mdb-dropdown-toggle>
            <mdb-dropdown-menu>
              <mdb-dropdown-item
                >Item 1
                <span style="float:right">{{ price1 }}</span></mdb-dropdown-item
              >
              <mdb-dropdown-item
                >Item 2
                <span style="float:right">{{ price2 }}</span></mdb-dropdown-item
              ><mdb-dropdown-item
                >Item 3
                <span style="float:right">{{ price3 }}</span></mdb-dropdown-item
              ><mdb-dropdown-item
                >Item 4
                <span style="float:right">{{ price4 }}</span></mdb-dropdown-item
              >
              <mdb-dropdown-item
                ><a href="#" style="color:blue"
                  >Proceed with the payment ></a
                ></mdb-dropdown-item
              >
            </mdb-dropdown-menu>
          </mdb-dropdown>

          <b-navbar-nav class="p-2">
            <b-nav-item href="#"><span class="fa fa-user"></span></b-nav-item>
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
  },
  data: function() {
    return {
      price1: "$" + this.getRandomPrice(),
      price2: "$" + this.getRandomPrice(),
      price3: "$" + this.getRandomPrice(),
      price4: "$" + this.getRandomPrice()
    };
  },
  methods: {
    getRandomPrice: function() {
      return Math.floor(Math.random() * (200 - 1) + 1) + ".00";
    }
  }
};
</script>

<style scoped>
.numberCircle {
  border-radius: 20%;
  padding: 13px;
  position: relative;
  background: rgb(235, 162, 5);
  color: white;
  text-align: center;
  font: 14px Arial, sans-serif;
}
</style>
