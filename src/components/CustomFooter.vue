<template>
  <div>
    <div class="container-fluid-footer position relative">
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
            <div >
              <i class="fab fa-facebook-square"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-instagram"></i>
              <i class="fab fa-linkedin"></i>
            </div>
          </div>
          <div class="col d-flex">
            <ul>Explore
              <li v-for="(item, index) in items" :key="index" >{{item.tag}} </li>
              <!-- <li>Blog</li> 
              <li>About us</li>
              <li>Success story</li>
              <li>Courses</li>
              <li>Contact us</li>-->
            </ul>
            <ul>Information
              <li v-for="(item, index) in itemsD" :key="index" >{{item.tag}}</li>
              <!-- <li>Purchase guide</li> 
              <li>Privacy policy</li>
              <li>Terms of service</li>-->
            </ul>
          </div>
        </div>
        <span>C Maxcoach. All Rights Reserved</span>
      </div>
      <div class="tondo-freccia">

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
