<template>
    <section class="container contact" id="contact">
            <div class="titre-page">
                <h2>Me contacter</h2>
            </div>
            <div class="contact-contenu">
            <div class="contact-gauche">
                        <h4>Mes coordonnées</h4>
                        <div class="contact-info">
                            <div class="contact-item">
                                <div class="icon">
                                    <ion-icon name="location"></ion-icon>
                                    <span>Adresse</span>
                                </div>
                                <p>
                                    : Angers, France
                                </p>
                            </div>
                            <div class="contact-item">
                                <div class="icon">
                                    <ion-icon name="mail"></ion-icon>
                                    <span>Email</span>
                                </div>
                                <p>
                                    <span>: brian.donatien@gmail.com</span>
                                </p>
                            </div>
                            <div class="contact-item">
                                <div class="icon">
                                    <ion-icon name="call"></ion-icon>
                                    <span>Téléphone</span>
                                </div>
                                <p>
                                    <span>: 06 29 16 70 12</span>
                                </p>
                            </div>
                            <div class="contact-item">
                                <div class="icon">
                                    <ion-icon name="language"></ion-icon>
                                    <span>Langues</span>
                                </div>
                                <p>
                                    <span>: Français, Anglais</span>
                                </p>
                            </div>
                        </div>
            </div>
            <div class="contact-droite">
                        <form action="mailto:brian.donatien@gmail.com" method="post" enctype="text/plain" class="contact-form">
                            <div class="input-control i-c-2">
                                <input type="text" required placeholder="Nom">
                                <input type="email" required placeholder="Adresse Mail">
                            </div>
                            <div class="input-control">
                                <input type="text" required placeholder="Sujet">
                            </div>
                            <div class="input-control">
                                <textarea name="" id="" cols="15" rows="8" placeholder="Votre Message"></textarea>
                            </div>
                            <div class="submit-btn">
                                <div class="container-btn">
                                    <a href="#" class="main-btn">
                                        <span class="btn-text"><input type="submit" value="Envoyer"></span>
                                        <span class="btn-icon"><ion-icon name="arrow-down-circle"></ion-icon></span>
                                    </a>
                                </div>
                            </div>
                        
                    </form>
                </div>
            </div>
            <div class="forme"></div>
        </section>
</template>