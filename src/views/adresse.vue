<template>
  <div class="home">
    <div class="header">
      <h3>WWW-Navigator</h3>
    </div>

    <div class="topnav">
      <NavComponent />
    </div>

    <div class="row">
      <div class="column side">
        <SideMenu />
      </div>

      <div class="column middle">
        <h2>das ist adresse page</h2>
      </div>

      <div class="column side"></div>
    </div>
  </div>
</template>

<script>
import NavComponent from "@/components/navMenu.vue";
import SideMenu from "@/components/sideMenu.vue";
export default {
  name: "Home",
  components: {
    NavComponent,
    SideMenu
  }
};
</script>
<style>
.button-1 {
  border-radius: 8px;
  background-color: #98afc7;
  margin: 8px;
  font-weight: bold;
  border-style: double;
  display: ruby;
  width: 100%;
  height: 2rem;
}
.button {
  border-radius: 8px;
  background-color: #98afc7;
  margin: 8px;
  font-weight: bold;
  border-style: double;
  display: table;
  width: 40%;
  height: 2rem;
  overflow-wrap: break-word;
  word-wrap: break-word;
}
/* Style the header */
.header {
  background-color: coral;
  padding: 20px;
  text-align: center;
  border-top-left-radius: 6px;
  border-top-right-radius: 6px;
}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: coral;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create three unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
}

/* Left and right column */
.column.side {
  width: 20%;
  background-color: cornflowerblue;
  height: 30rem;
  margin: 2px;
}

/* Middle column */
.column.middle {
  width: 55%;
  margin: 2px;
  background-color: darkcyan;
  height: 30rem;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column.side,
  .column.middle {
    width: 100%;
  }
}
</style>