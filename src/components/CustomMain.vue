<template>
  <div>
    <div class="container-fluid">
      <div class="wrapper-interno">
        <div class="row d-flex align-items-center" id="statistiche">
          <div class="col h-50 d-flex justify-content-center">
            <img class="h-75" src="../assets/img/background-pattern-grid-line-06.png" alt="">
            <p>1926</p>
            <p>finished sessions</p>
            <img class="h-75" src="../assets/img/background-pattern-grid-line-06.png" alt="">
          </div>
          <div class="col h-50 d-flex">

            <p>100%</p>
            <p>satisfaction rate</p>
            <img class="h-75" src="../assets/img/background-pattern-grid-line-06.png" alt="">
          </div>
          <div class="col h-50 d-flex">

            <p>3092+</p>
            <p>enrolled learners</p>
            <img class="h-75" src="../assets/img/background-pattern-grid-line-06.png" alt="">
          </div>
          <div class="col h-50 d-flex">

            <p>200</p>
            <p>online instructors</p>
            <img class="h-75" src="../assets/img/background-pattern-grid-line-06.png" alt="">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CustomMain",
};
</script>

<style lang="scss">
@import "../style/common.scss";

#statistiche {
  width: 100%;
  height: 300px;
}
</style>
