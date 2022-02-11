<template>
    
    <nav>
        <div id="plop">
        <h1>Générateur de CV</h1>
        <img alt="carte du monde" src="@/assets/carte.jpg"/>
        </div>
        <section id="enTete">
        <div class="container">
        
        <button>Démarrer</button>
        <p>S'inscrire gratuitement : </p> 
        <button class="EnSavoirPlus"> <a href="#savoir_plus">En savoir plus</a></button>
        <h2>Comment ça marche, les 8 Fantastiques ?</h2>
        <p>Nous simplifions le parcours à un niveau inégalé</p>
        </div>
        </section>
        <section id="Parcours">
            <div class="un">
                <h1><button class="h1">1</button></h1>
                <p>
                    Créer moi-même mon CV
                    et le télécharger en PDF,
                    ou en version web
                </p>
            </div>
            <div class="un">
                <h1><button class="h1">2</button></h1>
                <p>
                    Me faire remarquer
                    en un seul clic
                </p>
            </div>
            <div class="un">
                <h1><button class="h1">3</button></h1>
                <p>
                    Trouver des offres d’emploi
                    qui me correspondent,
                    postuler et m’organiser
                </p>
            </div>
        </section>
         <div class="accueil">
                <h1>Les 8 Fantastiques</h1>
                <div class="slogan">
                    <p>"You can't save the world alone."</p>
                </div>
                <div class="photo">
                    <img src="@/assets/guerriere.jpg" alt="illustration" />
                </div>
                <div class=presentation>
                    <div id="savoir_plus">
                    <h2> En savoir plus :</h2>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                            Asperiores, optio deleniti! Aliquam fugiat expedita, accusantium quae quasi eligendi
                            ex perspiciatis quas vel inventore repudiandae dicta sunt perferendis cum blanditiis
                            veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo vero, soluta
                            sunt quibusdam cumque cupiditate tempore molestiae quas natus dolorum eveniet recusandae!
                            Voluptates
                            sed dolorum at sunt numquam accusantium harum.</p>
                    </div>
                </div>
                <div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Asperiores, optio deleniti! Aliquam fugiat expedita, accusantium quae quasi eligendi
                        ex perspiciatis quas vel inventore repudiandae dicta sunt perferendis cum blanditiis
                        veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo vero, soluta
                        sunt quibusdam cumque cupiditate tempore molestiae quas natus dolorum eveniet recusandae!
                        Voluptates
                        sed dolorum at sunt numquam accusantium harum.</p>
                </div>
                <div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Asperiores, optio deleniti! Aliquam fugiat expedita, accusantium quae quasi eligendi
                        ex perspiciatis quas vel inventore repudiandae dicta sunt perferendis cum blanditiis
                        veritatis? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo vero, soluta
                        sunt quibusdam cumque cupiditate tempore molestiae quas natus dolorum eveniet recusandae!
                        Voluptates
                        sed dolorum at sunt numquam accusantium harum.</p>
                </div>
            </div>
    </nav>
</template>

<script>

</script>


<style scoped>
*{
background: linear-gradient(rgb(83, 148, 134),rgb(59, 86, 97));
  font-family: "Prata", serif;
}
body {
  font-family: "Open Sans", sans-serif;
  color: #444444;
}

a {
  color: #34b7a7;
  text-decoration: none;
}

a:hover {
  color: #51cdbe;
  text-decoration: none;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Raleway", sans-serif;
}
.presentation {
  color: white;
  padding: 20%;
}
#main {
  margin-top: 50px;
}

</style>
