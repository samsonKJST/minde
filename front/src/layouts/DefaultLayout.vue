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
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,100..900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');

header {
    position: static;
    display: flex;
    width: 100%;
    background-color: #171321;
    justify-content: space-between;
    align-items: center;
    margin: 0;
    
    
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


</style>