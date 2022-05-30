<template>
  <div id="wrapper-header" class="container-fluid">
    <div id="barra-header" class="container-fluid">
      <div class="row h-100 d-flex align-items-center">
        <div id="logo" class="col h-50 d-flex justify-content-center">
          <img class="h-100" src="../assets/img/dark-logo.png" alt="" />
        </div>
        <div id="nav" class="col ">
          <ul class="d-flex justify-content-around ">
            <li>Home</li>
            <li>Pages</li>
            <li>Courses</li>
            <li>Features</li>
            <li>Blog</li>
            <li>Shop</li>
          </ul>
        </div>
        <div id="social" class="col d-flex justify-content-center">
          <i class="fab fa-twitter"></i>
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-linkedin"></i>
        </div>
      </div>
    </div>
    <div id="jumbotron" class="container-fluid">
      <div class="row">
        <div id="claim" class="col">
          <small>i'm wingman</small>
          <h1>peace on earth a wonderful whis but no way</h1>
          <p>
            Success isn't overnight. It's when everyday you get a little better
            than the day before. It all adds up.
          </p>
          <button>get started for free</button>
        </div>
        <div id="testimonial" class="col">
          <img src="../assets/img/home-movation-hero-image.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomHeader",
};
</script>

<style lang="scss">
@import "../style/common.scss";

#wrapper-header {
  height: 80vh;
  background-image:url(../assets/img/background-pattern-wavify.png);

  #barra-header {
    height: 50px;
  }

  #jumbotron {
    height:  calc(100% - 50px);
  }

}

</style>
