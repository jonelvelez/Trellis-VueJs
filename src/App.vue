<template>
    <div id="nav">
      <top-header></top-header>
      <banner></banner>
      <first-section></first-section>
      <second-section></second-section>
      <third-section></third-section>
      <fourth-section></fourth-section>
      <footer-section></footer-section>
    </div>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import Banner from '@/components/Banner.vue';
import FirstSection from '@/components/home-first-section.vue';
import SecondSection from "@/components/home-second-section.vue";
import ThirdSection from "@/components/home-third-section.vue";
import FourthSection from "@/components/home-fourth-section.vue";
import Footer from "@/components/footer.vue";

export default {
  components: {
   'top-header': HeaderTop,
   'banner': Banner,
   'first-section': FirstSection,
   'second-section': SecondSection,
   'third-section': ThirdSection,
   'fourth-section': FourthSection,
   'footer-section': Footer,
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Oswald:wght@200;300;400;500;600;700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.navbar {
  box-shadow: 0px 9px 20px 2px rgba(0,0,0,0.24);
}

.navbar-dark .navbar-toggler-icon {
  background-color: #666 !important;
}

/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
