<script>


export default {
  name: "AppHeader",

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

    <header class="d-flex flex-wrap justify-content-center px-3 py-3 mb-0">
      <a href="/" class="d-flex align-items-center mb-3 mb-md-0 me-md-auto text-dark text-decoration-none">
        <img src="../assets/Logo.png" alt="">
      </a>

      <ul class="nav nav-pills text-uppercase fw-bold d-flex justify-content-center align-items-center ">
        <li><a href="" class="nav-link">home</a></li>
        <li><a href="" class="nav-link">blog</a></li>


        <li class="dropdown">
          <a href="javascript:void(0)" class="dropbtn">events</a>
          <div class="dropdown-content">
            <a href="#">choral music</a>
            <a href="#">concert band</a>
            <a href="#">opera concerts</a>
            <a href="#">symphony orchestra</a>
            <a href="#">family concerts</a>
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

        <li><a href="" class="nav-link"><img src="../assets/image (23).svg" alt=""></a></li>
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

li a img {
  filter: invert(100%) sepia(44%) saturate(2333%) hue-rotate(185deg) brightness(112%) contrast(100%);
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
  background-color: #1F1F1F;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
  right: 0px;
}

.dropdown-content a {
  color: white;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
  border-bottom: 1px solid white;
}

.dropdown-content a:hover {
  background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>
