<template>
    <section class="container portfolio" id="portfolio">
            <div class="titre-page">
                <h2>Mes réalisations</h2>
            </div>
            <div class="portfolio-gallerie port-active" id="portfolio-gallerie" >
                  <div class="portfolio-items" v-for="projet in portfolio" v-bind:key="projet.id">
                            <div class="portfolio-item port-active" v-bind:id="projet.id">
                              <div class="image">
                                      <img :src="require(`../assets/images/${projet.screenPreview}`)" />
                              </div>
                              <div class="hover-items">
                                  <h3>{{portfolio.nom}}</h3>
                                  <div class="icon">
                                      <div class="btn-port" v-bind:data-id="projet.idJS">
                                          <ion-icon name="arrow-forward-circle"></ion-icon>
                                      </div>
                                  </div>
                              </div>
                            </div>
                  </div>
            </div>
            <PortfolioDetailsComp/>
            <div class="forme"></div>
        </section>
</template>

<script>
import portfolioData from "../assets/portfolio.json";
import PortfolioDetailsComp from './PortfolioDetailsComp.vue';

export default {
  data() {
    return {
      portfolio: portfolioData,
    };
  },
  components: {
    PortfolioDetailsComp,
  }
};
</script>