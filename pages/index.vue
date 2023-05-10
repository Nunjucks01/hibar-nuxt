<template>
  <div>
    <Header />
    <Section1></Section1>
    <Section2></Section2>
    <Section3></Section3>
    <Section4></Section4>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "../components/Header.vue";
import Section1 from "../components/Section1.vue";
import Section2 from "../components/Section2.vue";
import Section3 from "../components/Section3.vue";
import Section4 from "../components/Section4.vue";
import Footer from "../components/Footer.vue";

export default {
  components: {
    Header,
    Section1,
    Section2,
    Section3,
    Section4,
    Footer,
  },
  head() {
      return {
        title: 'Tlenoterapia hiperbaryczna',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Innowacyjna i jedna z najbardziej efektywnych metod rehabilitacji. Biłgoraj'
          }
        ]
      }
  }
};
</script>
