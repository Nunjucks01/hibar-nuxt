<template>
  <section class="Section2" id="tlenoterapia">
    <div class="container">
      <div class="wrapper">
        <div class="question-mark-wrap">
          <img src="~/assets/img/question-mark.png" alt="question mark" />
        </div>
        <div class="main-content">
          <h2>Co to jest tlenoterapia hiperbaryczna?</h2>
          <p>
            Tlenoterapia hiperbaryczna to innowacyjna i jedna z najbardziej
            efektywnych metod rehabilitacji, która odnajduje zastosowanie w
            wielu dziedzinach medycyny. <br /><br />
            Opiera się na dostarczeniu do organizmu dużej ilości czystego tlenu,
            w warunkach zwiększonego ciśnienia, który dociera do chorych i
            niedotlenionych tkanek i narządów, wpływając na ich poprawne
            funkcjonowanie oraz wspomagając jednocześnie leczenie wszelkich
            schorzeń, chorób i gojenie ran.
          </p>
          <div class="buttons">
            <router-link to="/zastosowanie">
              <button class="btn1" type="button">
                <span class="btn-text">Poznaj zastosowania</span>
              </button>
            </router-link>

            <!-- <button class="btn2" type="button">
              <i class="icon-youtube"></i>
              <span class="btn-text">Poznaj historię młodego pacjenta</span>
            </button> -->
          </div>
        </div>
        <div class="img-wrap">
          <img class="img-fluid" src="~/assets/img/patient.jpg" alt="HiBar" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>