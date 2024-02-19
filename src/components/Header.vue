<script>


export default {
  name: "Header",

  data() {
    return {

    };
  },
  methods: {

  }
};
</script>

<template>
  <div class="container-fluid p-0 bg-black ">

    <header class="d-flex flex-wrap justify-content-center px-3 py-3 mb-4 border-bottom">
      <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
        <img src="../assets/Logo.png" alt="">
      </a>

      <ul class="nav nav-pills text-uppercase fw-bold ">
        <li><a href="" class="nav-link">home</a></li>
        <li><a href="" class="nav-link">blog</a></li>


        <li class="dropdown">
          <a href="javascript:void(0)" class="dropbtn">events</a>
          <div class="dropdown-content">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
          </div>

        </li>

        <li><a href="" class="nav-link">gallery</a></li>
        <li><a href="" class="nav-link">about us</a></li>
        <li><a href="" class="nav-link">contact us</a></li>


        <li class="dropdown">
          <a href="javascript:void(0)" class="dropbtn">shop</a>
          <div class="dropdown-content">
            <a href="#">Link 1</a>
            <a href="#">Link 2</a>
            <a href="#">Link 3</a>
          </div>

        </li>

        <li><a href="" class="nav-link">icon</a></li>
      </ul>

    </header>

  </div>
</template>

<style lang="scss" scoped>
@use "../styles/partials/variables" as *;
@use "../styles/partials/mixins" as *;

li a,
.dropbtn {
  display: inline-block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover,
.dropdown:hover .dropbtn {
  color: $link-hover-color;
}

li.dropdown {
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
