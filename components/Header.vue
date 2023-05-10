<template>
  <header class="main-header">
    <div class="container">
      <div class="step-caption">
        <div class="step">
          <img class="step-img" src="~/assets/img/phone.png" alt="HiBar" />
          <a href="tel:+48577542517">+48 577542517</a>
        </div>
        <div class="step">
          <img class="step-img" src="~/assets/img/message.png" alt="HiBar" />
          <a href="mailto:hibarmedico2@gmail.com">hibarmedico2@gmail.com</a>
        </div>
        <div class="step">
          <img class="step-img" src="~/assets/img/messenger.png" alt="HiBar" />
          <a href="https://www.facebook.com/HiBarTlenoterapia/" target="_blank" rel="nofollow"
            >Facebook fanpage</a
          >
        </div>
        <div class="step">
          <img class="step-img" src="~/assets/img/earth.png" alt="HiBar" />
          <a href="https://goo.gl/maps/DBb26o4RrdBUjPzE9" target="_blank" rel="nofollow"
            >Trasa dojazdu</a
          >
        </div>
      </div>
    </div>
    <div class="separator"></div>
    <div class="container">
      <div class="wrapper">
        <router-link to="/">
          <img src="~/assets/img/Logo_HiBar.png" alt="HiBar" />
        </router-link>
        <ul
          class="hamburger"
          @click="navOpened = !navOpened"
          :class="{ active: navOpened }"
        >
          <li></li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
        <nav :class="{ active: navOpened }">
        <nuxt-link to="/#tlenoterapia">TLENOTERAPIA</nuxt-link>
        <nuxt-link to="/zastosowanie">ZASTOSOWANIE</nuxt-link>
        <nuxt-link to="#cennik">CENNIK</nuxt-link>
        <nuxt-link to="#kontakt">KONTAKT</nuxt-link>
        </nav>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  data() {
    return {
      navOpened: false,
    };
  },
};
</script>
