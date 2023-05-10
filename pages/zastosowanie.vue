<template>
<div>
  <Header></Header>
  <Introduction></Introduction>
  <Examples></Examples>
  <Section3></Section3>
  <Section4></Section4>
  <Footer></Footer>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Footer from "../components/Footer.vue";
import Section3 from "../components/Section3.vue";
import Section4 from "../components/Section4.vue";
import Introduction from '../components/Introduction.vue';
import Examples from '../components/Examples.vue';

export default {
  components: {
    Header,
    Footer,
    Section3,
    Section4,
    Introduction,
    Examples,
  },
  mounted() {
    window.scrollTo(0,0);

  },
  head() {
      return {
        title: 'Zastosowanie',
      }
  }
};
</script>