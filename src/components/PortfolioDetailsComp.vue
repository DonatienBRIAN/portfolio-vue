<template>
  <div class="portfolio-details" >
    <div v-for="projet in portfolio" v-bind:key="projet.id" >
                        <div class="details port-inactive" v-bind:id="projet.idJS">
                          <h3>{{projet.nom}}</h3>
                          <div class="details-gauchedroite">
                              <img :src="require(`../assets/images/${projet.screenFull}`)" />
                              <div class="details-grille">
                                  <h4>Type de projet</h4>
                                  <p>{{projet.typeProjet}}</p>
                                  <h4>Technologies utilisées</h4>
                                  <p>{{projet.technologieUtilisee}}</p>
                                  <h4>Détails</h4>
                                  <p>{{projet.details}}</p>
                                  <div class="btn-retour main-btn" v-bind:data-id="projet.idJS">
                                      <span class="btn-text">Retour</span>
                                      <span class="btn-icon"><ion-icon name="arrow-down-circle"></ion-icon></span>
                                  </div>
                              </div>
                          </div>
                      </div>
                      </div>
  </div>
</template>

<script>
import portfolioData from "../assets/portfolio.json";

export default {
  data() {
    return {
      portfolio: portfolioData,
    };
  },
};
</script>