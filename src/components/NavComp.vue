<template>
    <div class="navigation">
        <div class="image-logo">
            <img :src="require(`../assets/images/logoDB.png`)" alt="Logo site">
        </div>
        <nav class="boutons">
            <button class="bouton active-btn" data-id="accueil" >
                <ion-icon name="home"></ion-icon>
                <div class="btn-text"><p>Accueil</p></div>
            </button>
            
            <button class="bouton" data-id="parcours">
                <ion-icon name="school"></ion-icon>
                <div class="btn-text"><p>Parcours</p></div>
            </button>
            
            <button class="bouton" data-id="portfolio">
                <ion-icon name="briefcase"></ion-icon>
                <div class="btn-text"><p>Réalisations</p></div>
            </button>
            
            <button class="bouton" data-id="contact">
                <ion-icon name="mail-open"></ion-icon>
                <div class="btn-text"><p>Contact</p></div>
            </button>
            
        </nav>
    </div>
</template>

<script>
</script>