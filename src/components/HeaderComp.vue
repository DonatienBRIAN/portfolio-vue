 <template>
    <header class="header " >
            <div class="container contenu-header active" id="accueil">
                <div class="header-gauche">
                    <div class="image">
                        <img :src="require(`../assets/images/photoIdentite.png`)" alt="Photo Identité" >
                    </div>
                </div>
                <div class="header-droite">
                    <h1><span class="texte-sup">Hello!</span> Je m'appelle <span class="texte-sup">Donatien BRIAN</span> et je suis <span class="texte-sup">Développeur Web</span>.</h1>
                    <p>Vous trouverez sur ce site mon cv, mon parcours, mes réalisations ainsi que mes coordonnées.</p>
                    <div class="container-btn">
                        <a href="./CV Donatien BRIAN.pdf" class="main-btn">
                            <span class="btn-text">Télécharger CV</span>
                            <span class="btn-icon"><ion-icon name="arrow-down-circle"></ion-icon></span>
                        </a>
                    </div>
                </div>
                <div class="forme"></div>
            </div>
    </header>
</template>