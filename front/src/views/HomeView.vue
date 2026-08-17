<script setup>

</script>

<template>
   <main>
        <section class="part1">
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
        </section>
        <section class="part2">
            <p>COMMUNAUTE</p>
            <div><h2>Histoires récentes</h2></div>
            
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
    height: 580px;
    padding-top: 80px;
    padding-left: 20px;
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
</style>