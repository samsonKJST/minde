<template>
    <header>
        <section class="titre-logo">
            <div class="logo"><p>M</p></div>
            <div class="titre">
            <p>Mi n'dè</p>
        </div>
        </section>
        <section class="groupe-boutons">
            <input type="radio" id="btn1" name="mon-groupe" checked>
            <label for="btn1">Acceuil</label>
            <!-- Bouton 2 -->
            <input type="radio" id="btn2" name="mon-groupe">
            <label for="btn2">Histoires</label>

            <!-- Bouton 3 -->
            <input type="radio" id="btn3" name="mon-groupe">
            <label for="btn3">Mythologie</label>
        </section>
        <section class="auth">
            <button class="connexion">
                connexion
            </button>
            <button class="inscrire">S'inscirire</button>
        </section>
    </header>
    
    <RouterView />
    <footer>
        <section>
            <div class="logo-desc">
                <div>
                    <div class="logo">
                        <p>M</p>
                    </div>
                    <div class="titre">
                        <p>Mi n'dè</p>
                    </div>
                </div>
                <p>Plateforme de partage d'histoires et de découverte de mythologies.</p>
            </div>
            <div>
                <h4 class="title-footer">Plateforme</h4>
                <ul>
                    <li><button>Acceuil</button></li>
                    <li> <button>histoire</button></li>
                    <li><button>mythologie</button></li>
                </ul>
            </div>
            <div>
                <h4 class="title-footer">Compte</h4>
                <ul>
                    <li><button>Connexion</button></li>
                    <li><button>Inscription</button></li>
                    <li><button>Mon Profil</button></li>
                </ul>
            </div>
            <div>
                <h4 class="title-footer">Genre</h4>
                <ul>
                    <li><button>Horreur</button></li>
                    <li><button>Romance</button></li>
                    <li><button>Thriller</button></li>
                    <li><button>Drame</button></li>
                </ul>
            </div>
        </section>
        <div class="trait-footer"> </div>
        <span class="copirit">© 2026 Mi n'dè. Tous droits réservés.</span>
    </footer>
    
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');

header {
    position: fixed;
    display: flex;
    width: 100%;
    background-color: #171321;
    justify-content: space-between;
    align-items: center;
    margin: 0;
    z-index: 1;
    
    
}
.titre-logo {
    display: flex;
    align-items: center;
    gap:10px;
    margin-left: 20px;
}

.auth{
    display: flex;
    gap: 20px;
    margin-right: 20px;
}
.connexion{
    color:white;
    background: none;
    border: none;
    font-family: 'Outfit', sans-serif;
    font-size: 14px;
    font-weight: 450;
}
.logo {
width: 32px; 
height: 32px; 
background: linear-gradient(135deg, rgb(91, 33, 182) 0%, rgb(245, 158, 11) 100%); 
border-radius: 8px;
display: flex;
justify-content: center;
align-items: center;
}
.logo p{
    color: white;
    font-family: 'Fraunces', serif;
    font-size: 14px;
    font-weight: bold;
    

}
.titre {
    color:white;
    font-family: 'Fraunces', serif;
    font-weight:bold;
    font-size: 20px;
}
.inscrire{
    background-color: #5B21B6;
    color:white;
    border: none;
    font-family: 'Outfit', sans-serif;
    font-size: 14px;
    font-weight: 450;
    padding: 10px 20px;
    border-radius: 10px;
}

/* 1. Masquer les boutons radio par défaut */
.groupe-boutons input[type="radio"] {
  display: none;
  
}

/* 2. Style de base de vos boutons (les labels) */
.groupe-boutons label {
  display: inline-block;
  padding: 10px 20px;
  color: #fff;
  cursor: pointer;
  border-radius: 10px;
  margin-right: 10px;
  font-size: 14px;
  font-weight:400;
  font-family: 'Outfit', sans-serif; /* Votre police Outfit ! */
  transition: background-color 0.3s ease;
}

/* 3. EFFET TOGGLE : Quand le bouton radio est sélectionné, 
      on applique le bleu au label juste après lui (+) */
.groupe-boutons input[type="radio"]:checked + label {
  background-color: #341369a1; 
  color: white; 
  font-weight:600;            
}

footer{
    background-color:#171321;
    height: 350px;
    padding: 0px;
    margin: 0px;
    
}
footer>section{
    display: flex;
    gap: 150px;
    padding-left: 20px;
    padding-top: 50px;
    height: 70%;
}
.logo-desc{
    width: 20%;
}
.logo-desc > p:first-of-type {
    color:rgba(255, 255, 255, 0.404);
    font-size: 14px;
    font-weight: 400;
    font-family: 'Outfit','sans-serif';
    
}
.logo-desc div:first-of-type{
    display: flex;
    align-items: center;
    gap: 8px;
}
.title-footer{
    font-family: 'Outfit','sans-serif';
    font-weight: 600;
    font-size: 12;
    color: rgba(255, 255, 255, 0.5);
    letter-spacing: 0.6px;
}
footer ul{
    list-style-type: none;
    padding: 0px;
    margin: 0px;
}
footer button{
    background: none;
    border: none;
    font-size: 15px;
    font-family: 'Outfit','sans-serif';
    font-weight: 400;
    color: rgba(255, 255, 255, 0.404);
    line-height: 3;
}
.trait-footer{
    height: 0.5px;
    width: 100%;
    margin-bottom: 20px;
    padding: 0px;
    background-color: rgba(80, 74, 74, 0.404);
}
.copirit{
    font-family: 'Outfit','sans-serif';
    font-weight: 400;
    font-size: 12px;
    color: rgba(255, 255, 255, 0.253);
    margin-left: 20px;

}

</style>