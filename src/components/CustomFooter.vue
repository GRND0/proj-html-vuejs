<template>
  <div>
    <div class="container-fluid-footer">
      <div class="wrapper-footer">
        <div class="row h-75 my-auto">
          <div class="col d-flex flex-column justify-content-center ">
            <h6 class="mb-3 fw-bold text-white">Address</h6>
            <span class="mb-2">
              382 NE 191st St #87394 Miami, FL 33179-3899
            </span>
            <span class="mb-2">
              +1(305) 547-9909 (9am - 5pm EST, Monday - Friday)
            </span>
            <span class="mb-5">
              support@maxcoach.com
            </span>
            <div>
              <i class="fab fa-facebook-square"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-instagram"></i>
              <i class="fab fa-linkedin"></i>
            </div>
          </div>
          <div class="col d-flex justify-content-evenly align-items-center">
            <ul class="d-flex flex-column flex-wrap"><p class="text-white fw-bolder ">Explore</p> 
              <li class="mb-2" v-for="(item, index) in items" :key="index">{{ item.tag }} </li>
            </ul>
            <ul> <p class="text-white fw-bolder">Information</p> 
              <li class="mb-2" v-for="(item, index) in itemsD" :key="index">{{ item.tag }}</li>
            </ul>
          </div>
        </div>
        <span>C Maxcoach. All Rights Reserved</span>
      </div>
      <div class="position-relative">
        <div class="tondo-freccia rounded-circle d-flex flex-column justify-content-center align-items-center">
          <i class="fas fa-long-arrow-alt-up text-white"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomFooter",
  props: {
    items: Array,
    itemsD: Array,
  },
};
</script>

<style lang="scss">
@import "../style/common.scss";

.tondo-freccia {
  background-color: #20ad96;
  width: 40px;
  height: 40px;
  position: absolute;
  bottom: 20px;
  right: 20px;

}

.container-fluid-footer {

  background-color: #171621;

  .wrapper-footer {
    height: 500px;
    width: 70%;
    margin: 0 auto;
    color: lightgray;

  }
}
</style>
