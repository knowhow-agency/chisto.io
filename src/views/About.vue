<template>
  <div class="about-page position-relative">
    <Banner :footer='false'>
      <AboutBanner></AboutBanner>
    </Banner>
    <Middle>
      <AboutMiddle></AboutMiddle>
    </Middle>
    <Footer :block='true'></Footer>

  </div>
</template>

<script>
import Banner from '../components/Banner.vue';
import AboutBanner from '../components/AboutBanner.vue';
import Middle from '../components/Middle.vue';
import AboutMiddle from '../components/AboutMiddle.vue';
import Footer from '../components/Footer.vue';

export default {
  name: 'about',
  components: {
    Banner,
    Middle,
    Footer,
    AboutBanner,
    AboutMiddle,
  },
};
</script>
<style lang="scss">
@import '../assets/scss/main.scss';
.about-page {

}

</style>
