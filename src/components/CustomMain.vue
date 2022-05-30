<template>
  <div>
    <div class="container-fluid">
      <div class="wrapper-interno">
        <div class="row d-flex align-items-center" id="statistiche">
          <div class="col h-50 box-statistiche text-center">
            <p class="testo-verde">1926</p>
            <p>finished sessions</p>
          </div>
          <div class="col h-50 box-statistiche text-center">
            <p class="testo-verde">100%</p>
            <p>satisfaction rate</p>
          </div>
          <div class="col h-50 box-statistiche text-center">
            <p class="testo-verde">3092+</p>
            <p>enrolled learners</p>
          </div>
          <div class="col h-50 box-statistiche-last text-center">
            <p class="testo-verde">200</p>
            <p>online instructors</p>
          </div>
        </div>
      </div>
    </div>
    <div class="wrapper-interno">
      <div class="row">
        <div class="col">
          <p>ABOUT ME</p>
          <p>how to be an alpha male: the 15 habits of true alphas</p>
        </div>
        <div class="col">
          <p>Want to learn how to be an alpha male? How to be more masculine? How to be the man you've always wanted to
            be?</p>
          <p>Your goal is to show the consistency of business, core values, and customer care. Punctuality,
            responsability, individuality, accuracy, enthusiasm - you have to clearly explain how these qualities are
            applicable to your work. And the important thing is you do love what you do.</p>
        </div>
      </div>
    </div>
    <div class="wrapper-interno">
      <div class="row">
        <div class="col">

        </div>
        <div class="col">
          
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



  .box-statistiche {
    background-image: url(../assets/img/background-pattern-grid-line-06.png);
    background-repeat: no-repeat;
  }

  .box-statistiche-last {
    background-image: url(../assets/img/background-pattern-grid-line-06.png);

  }

  p {
    text-transform: uppercase;
  }

  .testo-verde {
    color: #20ad96;
    font-size: 3rem;
    font-weight: 700;
  }

}
</style>
