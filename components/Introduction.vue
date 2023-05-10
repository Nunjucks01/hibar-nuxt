<template>
  <section class="introduction">
    <div class="container">
      <div class="square"></div>
      <div class="main-content">
        <div class="blue-links">
          <router-link to="/">
            <a href="#">GŁÓWNA</a>
          </router-link>
          <p>-</p>
          <a href="#">ZASTOSOWANIE</a>
        </div>
        <h1>Zastosowania tlenoterapii hiperbarycznej</h1>
        <p>
          Tlenoterapia hiperbaryczna to innowacyjna i jedna z najbardziej
          efektywnych metod rehabilitacji, która odnajduje zastosowanie w
          wielu dziedzinach medycyny. <br /><br />

          Opiera się na dostarczeniu do organizmu dużej ilości czystego tlenu,
          w warunkach zwiększonego ciśnienia, który dociera do chorych i
          niedotlenionych tkanek <br />
          i narządów, wpływając na ich poprawne funkcjonowanie oraz
          wspomagając jednocześnie leczenie wszelkich schorzeń, chorób i
          gojenie ran.
        </p>
      </div>
      <nav id="kategorie">
        <a href="#autyzm">AUTYZM</a>
        <div class="separator"></div>
        <a href="#chirurgia">CHIRURGIA</a>
        <div class="separator"></div>
        <a href="#dermatologia">DERMATOLOGIA</a>
        <div class="separator"></div>
        <a href="#kardiologia">KARDIOLOGIA</a>
        <div class="separator"></div>
        <a href="#nagla-gluchota-szumy-uszne">NAGŁA GŁUCHOTA / SZUMY USZNE</a>
        <div class="separator"></div>
        <a href="#neurologia">NEUROLOGIA</a>
        <div class="separator"></div>
        <a href="#onkologia">ONKOLOGIA</a>
        <div class="separator"></div>
        <a href="#reumatyzm">REUMATYZM</a>
        <div class="separator"></div>
        <a href="#sport">SPORT</a>
      </nav>
      <div class="footer">
        <p>
          <span>
            Wachasz się? Nie wiesz czy tlenoterapia hiperbaryczna jest właściwym
            rozwiązaniem dla Ciebie? <br />
          </span>
          Zadzwoń! Nasz wykfalifikowany personel wyjaśni wszelkie wątpliwości.
        </p>
        <div class="phone-number">
          <img src="~/assets/img/phone.png" alt="HiBar" />
          <a href="tel:+48577542517"><h3>+48 577542517</h3></a>
        </div>
      </div>
    </div>
    <a :class="{active: scrollTopButtonActive}" href="#kategorie" class="icon-scroll-top">
      <i class="icon-angle-up"></i>
    </a>
  </section>
</template>

<script>
export default {
  data() {
    return {
      scrollTopButtonActive: false,
    }
  },
  mounted() {
    const navOffset = document.getElementById('examples').offsetTop;
    document.addEventListener('scroll', () => {
      if(window.scrollY > navOffset - 200) {
        this.scrollTopButtonActive = true;
      } else {
        this.scrollTopButtonActive = false;
      }
    })
  },
};
</script>