<template>
  <div id="wrapper-header" class="container-fluid">
    <div class="wrapper-interno">
      <div id="barra-header" class="container-fluid">
        <div class="row h-100 d-flex align-items-center">
          <div id="logo" class="col h-50 d-flex justify-content-start">
            <img class="h-75" src="../assets/img/dark-logo.png" alt="" />
          </div>
          <div id="nav" class="col">
            <ul class="d-flex justify-content-around">
              <li v-for="(item, index) in items" :key="index" >{{item.tag}}</li>
              <!-- <li>Pages</li> 
              <li>Courses</li>
              <li>Features</li>
              <li>Blog</li>
              <li>Shop</li>-->
            </ul>
          </div>
          <div id="social" class="col d-flex justify-content-end">
            <i class="fab fa-twitter"></i>
            <i class="fab fa-facebook-f"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-linkedin"></i>
          </div>
        </div>
      </div>
      <div id="jumbotron" class="container-fluid pt-3">
        <div class="row">
          <div id="claim" class="col d-flex flex-column justify-content-center align-items-start pe-5">
            <small>i'm wingman</small>
            <span class="w-75">peace on earth a wonderful wish but no way</span>
            <p class="w-75">
              Success isn't overnight. It's when everyday you get a little better
              than the day before. It all adds up.
            </p>
            <a class="btn btn-primary ms_btn-custom" href="#" role="button">get started for free</a>

          </div>
          <div id="testimonial" class="col d-flex justify-content-end position-relative">
            <img id="disegno" class="h-75"  src="../assets/img/home-movation-shape-face.png" alt="">
            <img id="uomo" src="../assets/img/home-movation-hero-image.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomHeader",
  props: {
    items: Array,
  },
};
</script>

<style lang="scss">
@import "../style/common.scss";


.ms_btn-custom {
    padding: 1rem;
    background-color:#20ad96;
}

#wrapper-header {
  height: 80vh;
  background-image: url(../assets/img/background-pattern-wavify.png);
  background-color: #f7f7fd;

  #barra-header {
    height: 80px;

    .nav li {
      font-family: 'Montserrat', sans-serif;
    }
  }

  #jumbotron {
    height: calc(100% - 80px);

    .row {
      height: 100%;
    } 

    small {
      text-transform: uppercase;
    }

    span {
      font-family: 'Playfair Display', serif;
      text-transform: capitalize;
      font-size:4rem;
    }

    #disegno {
      z-index: 0;
      position: absolute;
      bottom: 0%;
      left: 25%;
    }

    #uomo {
      z-index: 1;
    }


  }

}
</style>
