<template>
  <div id="app">
    <CustomHeader :items='nav' />
    <CustomMain :items='cardFirst' :itemsD='cardSecond' :itemsT='cardBottom' />
    <CustomFooter :items='footerEx' :itemsD='footerInf' />
  </div>
</template>

<script>
import CustomHeader from "./components/CustomHeader.vue";
import CustomMain from "./components/CustomMain.vue";
import CustomFooter from "./components/CustomFooter.vue";

export default {
  name: "App",
  components: {
    CustomHeader,
    CustomMain,
    CustomFooter,
  },
  data: function () {
    return {
      nav: [
        {
          tag: "Home",
          link: "https:://"
        },
        {
          tag: "Pages",
          link: "https:://"
        },
        {
          tag: "Courses",
          link: "https:://"
        },
        {
          tag: "Features",
          link: "https:://"
        },
        {
          tag: "Blog",
          link: "https:://"
        },
        {
          tag: "Shop",
          link: "https:://"
        },
      ],
      footerEx: [
        {
          tag: "Start here",
          link: "https:://"
        },
        {
          tag: "Blog",
          link: "https:://"
        },
        {
          tag: "About us",
          link: "https:://"
        },
        {
          tag: "Success Story",
          link: "https:://"
        },
        {
          tag: "Courses",
          link: "https:://"
        },
        {
          tag: "Contact us",
          link: "https:://"
        },
      ],
      footerInf: [
        {
          tag: "Membership",
          link: "https:://"
        },
        {
          tag: "Purchase guide",
          link: "https:://"
        },
        {
          tag: "Privacy policy",
          link: "https:://"
        },
        {
          tag: "Term of service",
          link: "https:://"
        },
      ],
      cardFirst: [
        {
          img: "../assets/img/motivation-course-06-480x298.jpg",
          cost: "30",
          decimal: "00",
          title: "How to be Successful: Create A Growth Mindset For Success",
          lessons: "3",
          students: "50",
        },
        {
          img: "../assets/img/motivation-course-06-480x298.jpg",
          cost: "30",
          decimal: "00",
          title: "How to Build Confidence in Your Abilities",
          lessons: "1",
          students: "50",
        },
        {
          img: "../assets/img/motivation-course-06-480x298.jpg",
          cost: "20",
          decimal: "00",
          title: "Productivity Machine - Focus in a Distracted World",
          lessons: "5",
          students: "50",
        },

      ],
      cardSecond: [
        {
          img: "../assets/img/motivation-course-06-480x298.jpg",
          cost: "20",
          decimal: "00",
          title: "Effective Time Management Mastery - Complete Guide",
          lessons: "18",
          students: "50",
        },
        {
          img: "../assets/img/motivation-course-06-480x298.jpg",
          cost: "25",
          decimal: "99",
          title: "Body Language Secrets for Entrepreneurs",
          lessons: "19",
          students: "50",
        },
        {
          img: "../assets/img/motivation-course-06-480x298.jpg",
          cost: "19",
          decimal: "99",
          title: "Management Skills: The Science of Leadership",
          lessons: "17",
          students: "50",
        },
      ],
      cardBottom: [
        {
          img: "../assets/img/motivation-blog-04-480x325.jpg",
          date: "May 13, 2020",
          title: "how to stay true to your personal brand",
          claim: "When it comes to your business or career, you want ...",
        },
        {
          img: "../assets/img/motivation-blog-03-480x325.jpg",
          date: "May 13, 2020",
          title: "5 vital lessons in 5 years of freelancing",
          claim: "Being self-employed and working from home, it's easy to get ...",
        },
        {
          img: "../assets/img/motivation-blog-02-480x325.jpg",
          date: "May 13, 2020 ",
          title: "11 super useful tips for small-business owners",
          claim: "Being a small-business owner poses a ton of challenges. We ...",
        },
        {
          img: "../assets/img/motivation-blog-01-480x325.jpg",
          date: "May 13, 2020",
          title: "how to give yourself grace to start again",
          claim: "Forgive yourself for bad habits you may have started or ...",
        },
      ],
    }
  }
};
</script>

<style lang="scss">
</style>
