<template>
  <div>
    <div class="container-fluid">
      <div class="wrapper-footer">
        <div class="row">
          <div class="col">
            <h6>Adress</h6>
            <span>
              382 NE 191st St #87394 Miami, FL 33179-3899
            </span>
            <span>
              +1(305) 547-9909 (9am - 5pm EST, Monday - Friday)
            </span>
            <span>
              support@maxcoach.com
            </span>
            <div>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-instagram"></i>
              <i class="fab fa-linkedin"></i>
            </div>
          </div>
          <div class="col">
            <ul>Explore
              <li>Start here</li>
              <li>Blog</li>
              <li>About us</li>
              <li>Success story</li>
              <li>Courses</li>
              <li>Contact us</li>
            </ul>
            <ul>Information
              <li>Membership</li>
              <li>Purchase guide</li>
              <li>Privacy policy</li>
              <li>Terms of service</li>
            </ul>
          </div>
        </div>
        <span>C Maxcoach. All Rights Reserved</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomFooter",
};
</script>

<style lang="scss">
@import "../style/common.scss";

.container-fluid {

  background-color: #171621;

  .wrapper-footer {
    height: 300px;
    width: 70%;
    margin: 0 auto;

  }
}
</style>
