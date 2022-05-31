<template>
  <div>
    <section class="mb-5">
      <div class="container-fluid">
        <div class="wrapper-interno">
          <div class="row d-flex align-items-center mb-3" id="statistiche">
            <div class="col h-50 box-statistiche text-center">
              <p class="ms_testo-verde fw-bold fs-1">1926</p>
              <p class="text-uppercase ms_bolder">finished sessions</p>
            </div>
            <div class="col h-50 box-statistiche text-center">
              <p class="ms_testo-verde fw-bold fs-1">100%</p>
              <p class="text-uppercase ms_bolder">satisfaction rate</p>
            </div>
            <div class="col h-50 box-statistiche text-center">
              <p class="ms_testo-verde fw-bold fs-1">3092+</p>
              <p class="text-uppercase ms_bolder">enrolled learners</p>
            </div>
            <div class="col h-50 box-statistiche-last text-center">
              <p class="ms_testo-verde fw-bold fs-1">200</p>
              <p class="text-uppercase ms_bolder">online instructors</p>
            </div>
          </div>
        </div>
      </div>
      <div class="wrapper-interno mb-5">
        <div class="row">
          <div class="col">
            <div class="w-75">
              <p class="ms_testo-verde">ABOUT ME</p>
              <p class="text-capitalize fs-1 ms_font-alternativo">how to be an alpha male: the 15 habits of true alphas
              </p>
            </div>
          </div>

          <div class="col d-flex flex-column justify-content-around">
            <p class="fw-bolder">Want to learn how to be <span class="ms_testo-verde">an alpha male</span>? How to be
              more masculine? How to be the man you've always wanted
              to
              be?</p>
            <p class="ms_testo-grigio fw-semibold">Your goal is to show the consistency of business, core values, and
              customer care. Punctuality,
              responsability, individuality, accuracy, enthusiasm - you have to clearly explain how these qualities are
              applicable to your work. And the important thing is you do love what you do.</p>
          </div>
        </div>
      </div>
      <div class="wrapper-interno mb-5">
        <div class="row">
          <div class="col position-relative">
            <img class="rounded" src="../assets/img/home-movation-video-poster-670x450.jpg" alt="">
            <img class="youtube" src="../assets/img/icon-youtube-play.png" alt="">
          </div>
          <div class="col d-flex flex-column justify-content-center align-items-baseline">
            <p class="ms_font-alternativo fw-semibold fs-3 w-50 mb-5">"Every morning you have two choices: continue to
              sleep with your dreams, or wake up and chase them."</p>
            <img class="mb-3" src="../assets/img/home-movation-shape-01.png" alt="">
            <h6 class="mb-1 fw-bolder">Kaixa Stark</h6>
            <small class="ms_testo-grigio text-uppercase fs-6">wingman</small>
          </div>
        </div>
      </div>
    </section>
    <section class="mb-5">
      <div class="text-center mb-5">
        <p class="text-uppercase ms_testo-grigio fw-semibold fs-6">begin your journey at maxcoach</p>
        <p class="ms_font-alternativo fs-1">Latest <span class="ms_font-alternativo ms_testo-verde fs-1">Online
            Courses</span></p>
      </div>
      <div class="wrapper-interno mb-3">
        <div class="row">
          <div class="col" v-for="(item, index) in items" :key="index">
            <div class="card border-0">
              <img :src="item.img" class="card-img-top" alt="">
              <div class="card-body d-flex flex-column justify-content-between">
                <h5 class="card-title ms_testo-verde fw-bolder">{{ item.cost }}.<span class="fs-6">{{ item.decimal
                }}</span>
                </h5>
                <p class="card-text fw-bolder mb-4">{{ item.title }}</p>
                <div>
                  <small class="ms_testo-grigio me-3"><i class="fas fa-chalkboard-teacher"></i>{{ item.lessons
                  }} Lessons </small>
                  <small class="ms_testo-grigio"><i class="far fa-user"></i>{{ item.students }} Students </small>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="wrapper-interno mb-5">
        <div class="row">
          <div class="col" v-for="(item, index) in itemsD" :key="index">
            <div class="card border-0">
              <img :src="item.img" class="card-img-top" alt="">
              <div class="card-body d-flex flex-column justify-content-between">
                <h5 class="card-title ms_testo-verde fw-bolder">{{ item.cost }}.<span class="fs-6">{{ item.decimal
                }}</span>
                </h5>
                <p class="card-text fw-bolder mb-4">{{ item.title }}</p>
                <div>
                  <small class="ms_testo-grigio me-3"><i class="fas fa-chalkboard-teacher"></i> {{ item.lessons
                  }} Lessons </small>
                  <small class="ms_testo-grigio"><i class="far fa-user"></i> {{ item.students }} Students </small>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-2 mx-auto mb-4">
          <a class="btn btn-primary ms_btn-custom px-4" href="#" role="button">View all courses <i
              class="fas fa-long-arrow-alt-right ms-2"></i></a>
        </div>
      </div>

    </section>
    <section class="ms_spaziatore">
      <div class="wrapper-interno">
        <div class="row ms_spaziatore">
          <div class="col">
            <small class="text-uppercase">book store online</small>
            <h2 class="ms_font-alternativo text-capitalize mb-4">be alpha with <br> <span
                class="ms_testo-verde ms_font-alternativo">wingman's book</span></h2>
            <ul class="ms_testo-grigio p-0">
              <li class="mb-2">
                <i class="fas fa-check me-3 ms_testo-verde"></i> Help you understand yourself better
              </li>
              <li class="mb-2">
                <i class="fas fa-check me-3 ms_testo-verde"></i> Revealing mature tips
              </li>
              <li class="mb-2">
                <i class="fas fa-check me-3 ms_testo-verde"></i> Give the right advice
              </li>
              <li class="mb-2">
                <i class="fas fa-check me-3 ms_testo-verde"></i> Fascinating examples of alpha man
              </li>
            </ul>
            <a class="btn btn-primary ms_btn-custom" href="#" role="button">Get Free Ebook</a>
          </div>
          <div class="col d-flex">
            <div class="text-center me-2 position-relative" @mouseover="hover = false" @mouseout="hover = true">
              <div class="wrapper-hover position-absolute h-100 w-100" :class="{ hovering: hover }">
                <div id="" class="d-flex flex-column icone-hover">
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="fas fa-search"></i></div>
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="fas fa-cart-plus"></i></div>
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="far fa-heart"></i></div>
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="fas fa-signal"></i></div>
                </div>
              </div>
              <img class="mb-3 img-libri" src="../assets/img/product-book-11-400x400.jpg" alt="">
              <p class="fw-bolder">Alpha man by Maxcoach</p>
              <small class="ms_testo-verde fw-bolder fs-5">$29.<span class="fs-6">00</span></small>
            </div>

            <div class="text-center ms-2 position-relative" @mouseover="hoverDue = false" @mouseout="hoverDue = true">
              <div class="wrapper-hover position-absolute h-100 w-100" :class="{ hovering: hoverDue }">
                <div id="" class="d-flex flex-column icone-hover">
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="fas fa-search"></i></div>
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="fas fa-cart-plus"></i></div>
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="far fa-heart"></i></div>
                  <div class="rounded-circle ms_icona-tonda d-flex justify-content-center align-items-center mb-2"><i
                      class="fas fa-signal"></i></div>
                </div>
              </div>
              <img class="mb-3 img-libri" src="../assets/img/product-book-10-400x400.jpg" alt="">
              <p class="fw-bolder"> Real man 4.0 by Maxcoach</p>
              <small class="ms_testo-verde fw-bolder fs-5">$39.<span class="fs-6">00</span></small>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-2">
            <img class="ms_filtro" src="../assets/img/client-logo-05-primary.png" alt="">
          </div>
          <div class="col-2 ms_filtro">
            <img src="../assets/img/client-logo-06-primary.png" alt="">
          </div>
          <div class="col-2 ms_filtro">
            <img src="../assets/img/client-logo-07-primary.png" alt="">
          </div>
          <div class="col-2 ms_filtro">
            <img src="../assets/img/client-logo-04-primary.png" alt="">
          </div>
          <div class="col-2 ms_filtro">
            <img src="../assets/img/client-logo-03-primary.png" alt="">
          </div>
          <div class="col-2 ms_filtro">
            <img src="../assets/img/client-logo-02-primary.png" alt="">
          </div>
        </div>
      </div>

    </section>
    <section class="ms_spaziatore">
      <div class="container-fluid position-relative g-0 ms_spaziatore">
        <div class="rounded-circle selettore-tondo d-flex flex-column justify-content-center align-items-center">
          <img class="freccia mb-1" src="../assets/img/image.png" alt="">
          <small>1/4</small>
          <img class="freccia mt-1" src="../assets/img/image (1).png" alt="">
        </div>
        <div class="row g-0">
          <div class="col d-flex flex-column justify-content-center align-items-center testimonial-sx">
            <small class="ms_testo-verde text-uppercase ms_spaziatore">real stories</small>
            <span class="w-50 mb-5 text-center">
              I am fre to learn at my own pace, follow my own schedule and choose the subject i want to learn from the
              syllabus. Great study portal for people like me.
            </span>
            <div class="">
              <img id="testimonial-tondo" class="rounded-circle mb-3" src="../assets/img/testimonial-avata-02.jpg"
                alt="">
            </div>
            <small class="text-capitalize mb-3">mina hollace</small>
            <small class="ms_testo-grigio mb-3">/Freelancer</small>
          </div>
          <div class="col">
            <img class="" src="../assets/img/home-movation-testimonial-image.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="wrapper-interno">
        <div>
          <small class="text-uppercase mb-4 ">blog updated</small>
          <h4 class="ms_font-alternativo fs-1 mb-5">Intersting <span class="ms_testo-verde ms_font-alternativo">articles
              updated daily</span></h4>
        </div>

        <div class="row mb-4">
          <div class="col" v-for="(item, index) in itemsT" :key="index">
            <div class="card border-0">
              <img :src="item.img" class="card-img-top" alt="">
              <div class="card-body">
                <small class="ms_testo-grigio mb-2"><i class="far fa-calendar"></i> {{ item.date }}</small>
                <h5 class="card-title text-capitalize mb-3">{{ item.title }}</h5>
                <p class="card-text ms_testo-grigio">{{ item.claim }}</p>
              </div>
            </div>
          </div>
        </div>
        <div class="text-center">
          <div id="posts" class="d-inline-block">
            <span class="text-uppercase">view all posts</span>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "CustomMain",
  props: {
    items: Array,
    itemsD: Array,
    itemsT: Array,
  },
  data: function () {
    return {
      hover: true,
      hoverDue: true
    }

  },

};
</script>

<style lang="scss">
@import "../style/common.scss";

.ms_testo-verde {
  color: #20ad96;
}

.ms_testo-grigio {
  color: grey;
}

.ms_filtro {
  filter: sepia(100%);
  filter: opacity(30%);
}

.ms_bolder {
  font-weight: 500;
}

.ms_font-alternativo {
  font-family: 'Playfair Display', serif;
}

.ms_spaziatore {
  margin-bottom: 5rem;
}

.ms_icona-tonda {
  width: 35px;
  height: 35px;
  background-color: white;
}

#posts {
  color: #20ad96;
  border-bottom: 0.1rem solid #20ad96;

}

.icone-hover {
  position: absolute;
  top: 18%;
  right: 13%;
}

.hovering {
  display: none;
}

.card:hover {
  border: solid white 1px;
  box-shadow: 2px 2px 10px lightgray;

}

.card-body {
  min-height: 160px;
}

.ms_btn-custom {
  padding: 1rem;
  background-color: #20ad96;
  padding: 1rem 3rem;
  border: none;
  font-weight: bold;
  color: white;
}

.ms_btn-custom:hover {
  background-color: #3f3a64;
}



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


}

.youtube {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);

}

.testimonial-sx {
  background-image: url(../assets/img/background-pattern-wavify.png);
  background-color: #f7f7fd;
}

.selettore-tondo {
  background-color: $bianco;
  height: 55px;
  width: 55px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);



  .freccia {
    width: 6px;

  }
}

#testimonial-tondo {
  width: 70px;
}
</style>
