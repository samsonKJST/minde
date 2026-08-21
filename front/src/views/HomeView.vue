<script setup>

</script>

<template>
   <main>
        <section class="part1">
            <div>

            
            <span class="platforme-recit">PLATEFORME DE RECITS</span>
            <h2 class="racontez">Racontez ce que </h2>
            <h2 class="vecu">vous avez vécu.</h2>
            <div class="paragaphe">
                <p>Découvrez ce que les autres racontent. Un espace pour les </p>
                <p>auteurs, les lecteurs, et les passionnés de mythologies du</p>
                <p>monde entier.</p>
            </div>
            
            <div class="btn">
                <button class="btn1">Raconter mon histoire</button>
                <button class="btn2">Explorer des Histoires</button>
            </div>
            <div class="info">
                <div><p class="total">1 240+</p><p class="kpi">Histoires publiées</p></div>
                <div><p class="total">382</p><p class="kpi">Auteurs actifs</p></div>
                <div><p class="total">48</p><p class="kpi">Mythes </p></div>
            </div>
         </div>
        <div class="img-part1"></div>
        </section>
        <section class="part2">
            <p class="communaute">COMMUNAUTE</p>
            <div class="title-voirplus"><h2 class="title">Histoires récentes</h2><a href="">voir tout <i class="fa-solid fa-arrow-right-long"></i></a></div>
            <section class="cadres">
                <div class="cadre">
                    <img src="../assets/public/mystère.jpeg" alt="">
                    <div class="bas-cadre"> 
                        <h3>La Forêt des Murmures</h3>
                        <p class="auteur">par samson kouamé</p>
                        <p class="text-cadre">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure unde nostrum officia eum ut quaerat deleniti quod fuga illo! Velit nemo cupiditate cumque animi, nostrum iste consequuntur ducimus! Doloribus, optio.</p>
                        <div><p>12 août 2026</p><p><i class="fa-regular fa-eye"></i> 1,228</p></div>
                    </div>
                </div>
                <div class="cadre">
                    <img src="../assets/public/mystère.jpeg" alt="">
                    <div class="bas-cadre"> 
                        <h3>La Forêt des Murmures</h3>
                        <p class="auteur">par samson kouamé</p>
                        <p class="text-cadre">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure unde nostrum officia eum ut quaerat deleniti quod fuga illo! Velit nemo cupiditate cumque animi, nostrum iste consequuntur ducimus! Doloribus, optio.</p>
                        <div><p>12 août 2026</p><p><i class="fa-regular fa-eye"></i> 1,228</p></div>
                    </div>
                </div>
                <div class="cadre">
                    <img src="../assets/public/mystère.jpeg" alt="">
                    <div class="bas-cadre"> 
                        <h3>La Forêt des Murmures</h3>
                        <p class="auteur">par samson kouamé</p>
                        <p class="text-cadre">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure unde nostrum officia eum ut quaerat deleniti quod fuga illo! Velit nemo cupiditate cumque animi, nostrum iste consequuntur ducimus! Doloribus, optio.</p>
                        <div><p>12 août 2026</p><p><i class="fa-regular fa-eye"></i> 1,228</p></div>
                    </div>
                </div>
            </section>
            <section class="cadre-mythologie">
                <div class="info-mythologie">
                    <p>SECTION MYTHOLOGIE</p>
                    <h2>Plongez dans les mythes et légendes du monde entier</h2>
                    <p>Mythologie grecque, nordique, africaine, égyptienne… Des récits anciens qui éclairent le présent.</p>
                </div>
                <button>Explorer la mythologie <i class="fa-solid fa-arrow-right-long"></i></button>
            </section>
             <section class="tire-genre">
                <h2>Parcourir par genre</h2>
                <div class="group-genre">
                    <button class="genre">Horreur</button>
                    <button class="genre">Romance</button>
                    <button class="genre">Joie</button>
                    <button class="genre">Tristesse</button>
                    <button class="genre">Aventure</button>
                    <button class="genre">Mysthère</button>
                    <button class="genre">Fantastique</button>
                    <button class="genre">Drame</button>
                    <button class="genre">Thiller</button>
                    <button class="genre">Autre</button>
                </div>
            </section>
        </section>
    </main>
   
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Outfit:wght@100..900&display=swap');
main{
    margin: 0;
    padding: 0;
    
}

.part1{
    background: linear-gradient(135deg, rgb(23, 19, 33) 0%, rgb(45, 27, 105) 60%, rgb(59, 7, 100) 100%);
    height: 500px;
    padding-top: 100px;
    padding-left: 20px;
    display: flex;
    align-items: center;
    justify-content:space-between;
    padding-bottom: 90px;
}
.img-part1{
    box-shadow: 0 0 15px  #5a21b636;
    opacity: 0.8;
    border-radius: 15px;
    margin-right: 80px;
    height: 300px;
    width: 300px;
    background-image: url('../assets/public/bibliotheque.png');
}
.platforme-recit{
    font-family:'Outfit', sans-serif;
    font-weight: 700;
    font-size: 15px;
    color:#F59E0B;
    letter-spacing: 1.2px;
    line-height: 1.6
}
.racontez{
    font-family:'Fraunces', serif;
    font-size: 58px;
    font-weight: 600;
    color: #fff;
    margin: 0px;
}
.vecu{
    font-family:'Fraunces', serif;
    font-size: 58px;
    font-weight: 600;
    color: #F59E0B;
    font-style: italic;
    margin: 0px;
}

.paragaphe p{
    color: #ffffff94;
    margin: 0px;
    font-size: 18px;
    font-family:'Outfit', sans-serif;
    font-weight: 400;
    
}
.paragaphe{
    margin-top: 20px;
}
.btn{
    display: flex;
    gap: 10px;
    margin-top: 20px;
}
.btn1,.btn2{
    width: 200px;
    height: 50px;
    border-radius: 10px;
    border: none;
}
.btn1{
    background-color: #5B21B6;
    font-family:'Outfit', sans-serif;
    color: white;
    font-size: 16px;
    font-weight: 450;

}
.btn2{
    background-color: transparent;
    border: 1px solid #ffffff94;
    font-family:'Outfit', sans-serif;
    color: white;
    font-size: 16px;
    font-weight: 450;
}
.info{
    display: flex;
    gap:30px;
}

.total{
    font-style: italic;
    font-family:'Outfit', sans-serif;
    color: white;
    font-size: 30px;
    margin-bottom: 0px;
    font-weight: 700;
}
.kpi{
    margin-top:0px;
    font-family:'Outfit', sans-serif;
    color: #ffffff94;
    font-size: 15px;
    
}
.part2{
    padding-top: 80px;
    padding-left:20px;
    padding-right: 30px;
    background-color: #e4e2eb;
    

}
.communaute{
    color:#5B21B6 ;
    font-family:'Outfit', sans-serif;
    font-weight: 600;
    font-size: 15px;
    letter-spacing: 1.2px;
    margin: 0px;
}
.title {
    font-family:'Fraunces', serif;
    font-weight: 600;
    font-size: 37px;
    color: #1F2937;
    margin: 0px;
}
.title-voirplus{
    display: flex;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 30px;
}
.title-voirplus a {
    text-decoration: none;
    color: #5B21B6;
    font-weight: 600;
    font-size: 16px;
    font-family:'Outfit', sans-serif;

}
.cadres{
    display: flex;
    justify-content: space-between;
    gap: 20px;
    flex-wrap: wrap;
}
.cadre{
    height: 440px;
    width: 400px;
    border-radius: 16px;
    border: 1px solid rgba(0,0,0,0.07);
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.15);
}
.cadre:hover{
    border: 1px solid #5B21B6;
    box-shadow: 0 16px 40px rgba(91,33,182,0.15);
    transform: translateY(-4px);
    transition: all 300ms;

}
.cadre img{
    width: 400px;
    height:200px;
    border-radius: 10px 10px 0px 0px;
}
.cadre img:hover{
    transition: 500ms;
}
.bas-cadre h3{
    margin: 0px 0px 10px 0px;
    color: #1F2937;
    font-weight: 600;
    font-size: 20px;
    font-family:'Fraunces', serif;
    
}
.bas-cadre p {
    margin: 0px;
}
.bas-cadre{
    padding: 10px;
}
.bas-cadre div{
    display: flex;
    gap: 200px;
}
.bas-cadre div p{
    color: #6B7280;
    font-family:'Outfit', sans-serif;
    font-weight: 400;
    font-size: 16px;
    padding-top: 20px;
}
.auteur{
    color: #5B21B6;
    font-weight: 500;
    font-size: 14px;
    font-family:'Outfit', sans-serif;
}
.text-cadre{
    color: #6B7280;
    font-size: 16px;
    font-weight: 400;
    font-family:'Outfit', sans-serif;
    padding-top: 10px;
}
.cadre-mythologie{
    margin: 80px 20px 20px 20px;
    padding: 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 16px;
    background-image: url('../assets/public/mythologie.png');
    background-size: cover;
    background-position: center;
    height: 200px;
    box-shadow: 0 16px 40px rgba(245,158,11,0.15);
    border: 1.5px solid #F59E0B;
}
.info-mythologie{
    width: 50%;
}
.info-mythologie > p:first-of-type{
    color: #F59E0B;
    font-weight: 600;
    font-family:'Outfit', sans-serif;
    letter-spacing: 1.2px;
}
.info-mythologie > p:nth-of-type(2){
    color:#ffffffb7;
    margin: 0px;
    font-family: 'Outfit','sans-serif';
    font-size: 18px;
}
.info-mythologie > h2{
    font-size: 35px;
    font-weight: 600;
    font-family: 'Fraunces', serif;
    color: #fff;
    margin: 0px;
}
.cadre-mythologie button{
    background-color: #F59E0B;
    border: none;
    width: 200px;
    height: 50px;
    border-radius: 15px;
    color: #1C1400;
    font-family:'Outfit','sans-serif' ;
    font-weight: 600;
    font-size: 16px;
}
.cadre-mythologie button:hover{
    background-color: #c7830e;
}
.tire-genre{
    margin-top: 100px;
    margin-left: 30px;
    padding-bottom: 80px;
}
.tire-genre > h2{
    font-family: 'Fraunces','serif';
    font-weight: 600;
    font-size: 24px;
    color: #1F2937;
    line-height: 3.6;
    margin:0px ;
}
.group-genre{
    display: flex;
    gap: 15px;
    margin: 0px;
    padding: 0px;
}
.genre{
    border: none;
    background-color: white;
    border-radius: 15px;
    padding: 12px 20px;
    box-shadow: 0 16px 40px rgba(245,158,11,0.15);
    font-family: 'Fraunces','serif';
    color: #1F2937;
    font-weight: 500;
    font-size: 14px;
    margin: 0px;
}
.genre:hover{
    color: #5B21B6;
    border:1px #5B21B6 solid;
    margin: 0px;
}
</style>