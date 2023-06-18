<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">
    <title>Document</title>
    <style>
body{
background-color:whitesmoke;
  /* background-image: url(https://tse2.mm.bing.net/th/id/OIP.B1PP5l-T7iquuHHaozzuZQHaE8?pid=ImgDet&w=187&h=124&c=7&dpr=1.3://wallpaperaccess.com/full/3228833.jpg);*/
    background-size: cover;
}
.shot-header-title{
    color: orangered;
}
ul.topnav {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color:rgb(24, 94, 24);
  }
li a ,.apropos {
    display: inline-block;
    color:orangered;
    text-align: center;
    padding:0;
    text-decoration: none;
    }
  /*li a:hover, .propos:hover .apropos{
      background-color: red; }
  */.propos-content {
    display: none;
    position: absolute;
    background-color:rgb(17, 72, 45);
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}
  .propos-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
    }
  .propos-content a:hover {background-color:rgb(17, 72, 45);}
.propos:hover .propos-content {
  display: block;
} 
  li.propos {
    display: inline-block;
  }
  ul.topnav li {float: left;}
  ul.topnav li a {
    display: block;
    color: rgb(240, 246, 240);
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
transition: 0.4s ease-in-out;
  }
  ul.topnav li a:hover {/*background-color:rgb(41, 0, 128)*/ color:orangered;}
  ul.topnoav li.right {float: right;}
   @media screen and (max-width: 600px) {
    ul.topnav li.right, 
    ul.topnav li {float: none;}
  }
  /*.exemple {
    animation-duration: 3s;
    animation-name: exemple;
    animation-iteration-count: 3;
    animation-direction: alternate;
  }
  @keyframes exemple {
    from {
      margin-left:100%;
      width:300%
    }
  }
*/
  .exemple {
    display: inline-block;
    margin: 1em;
   /* min-width: 6.5em;*/
    line-height: 6.5em;
    text-align: center;
    transition: 1s ease-in-out;
   /* border: 0.25em dotted;*/
  }
   #exemple1:hover {
    rotate: y 180deg;
  }
  #exemple2:hover {
    rotate: y 180deg;
  }
  #exemple3:hover {
    rotate: y 180deg;
  }
  .bg {
    padding-left:1%;
    color: rgb(4, 4, 12);
  }
  .images {
    display: flex;
    justify-content: space-around;
    width: 50vw;
  }
  .img-clip-path {
    height: 200px;
  }
  .img-rectangle{
    clip-path:ellipse(50% 50%);
  }
  .box{
    border: 2px solid rgb(71, 26, 161);
    width: 45%;
    color: red;
    padding-left: 1% ;
  }
  .colone{
    column-count: 3;
    padding-left: 1%;
  color: red;
  }
  h3{
    padding: 10px 5px;
    border: 3px solid rgb(2, 7, 6);
    border-radius: 20px;
    width: 150px;
    font-size: 1.2rem;
    text-align: center;
    color: rgb(9, 12, 10);
  }
  .h11{
    color:rgb(17, 72, 45);
  }
  .rotate {
    transition: rotate 1s;
  }
  div:hover .rotate {
    rotate: 1 -0.5 1 180deg;
  }
  #fr{color: red;}
  .colonne{
    column-count: 3;
    padding-left: 1%;
  color: blue;
  }
  .pied{
    padding-top:5% ;
    background-color:black ;
    padding-bottom: 10%;
    padding-left: 4%;
  }
  .ut{
    color:blue;
  }
  .utt{
    color:black;
  }
  .bl{background-color: blue;}
  button{color:white}
.ab{
  color: orangered;
}
      </style>
</head>
<body>  
    <ul class="topnav">
        <li><a class="active" href="#home">Acceuil </a></li>
        <li><a href="#news">Travail </a></li>
        <li><a href="#Cv">Cv </a></li>
        <li><a href="#contact">Contact </a></li>
        <li class="propos"><a href="javascript:void(0)" class="apropos" >À propos</a>
        <div class="propos-content">
      <a href="#">Information générales<br>et coordonnées</a>
      <a href="##">confidentialité et<br>informations juridiques</a>
      <a href="#">Emploi et entreprise</a>
      <a href="#">Lieux de résidence</a>
      <a href="#">Transparence de la page</a>
      <a href="#">Famille et relation</a>
      <a href="#">Détails sur vous</a>
      <a href="#">Évènements marquants</a>
        </div> 
        </li>
      </ul>
      <br>
      <br>
      <div class="image" >
        <center><div class="rotate">
          <img class="img-rectangle img-clip-path"  alt="mercedez" title="marque-mercedez"  src="https://tse2.mm.bing.net/th/id/OIP.1n2tW4cdDSpR3CrHH71RKgHaEK?w=284&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7" alt="">
        </div></center>
          <h1 class="h11"><b>Amza - nouveau concèpteur <br> de merco pro max Tn 6666</b></h1>
        </div>
      <div style="padding:0 16px;color: rgb(5, 5, 14); ">
        <h1>Votre entreprise d'automobile !</h1>
      </div>
      <div class="box">
        <p>Bienvenue chez notre concessionnaire automobile ! Nous sommes ravis de vous accueillir dans notre entreprise<br> et  de vous aider à trouver le véhicule qui répondra à vos besoins Chez nous, vous trouverez une large sélection de voitures neuves<br> et d'occasion ainsi que des financements et des offres spéciales pour vous aider à obtenir le meilleur prix possible. Notre équipe de professionnels est <br>là pour répondre à toutes vos questions et pour vous aider à naviguer dans le processus d'achat. Nous espérons que vous apprécierez votre visite chez nous !</p>
      </div>
      <div class="bg">
      <h2>Un modèle athlétique et connecté</h2>
      </div>
<div >
        <p>Inspirée des modèles mythique qui ont forgé l'histoire de mercedez en compétition automobile, la deuxiéme génération de mercedez C616 sportback est plus athlétique que jamais. A
        l'intérieur, résolument digital native, la petite citadine embarque les technologies des plus grandes.</p>
      </div>
      <div>
<div  class="exemple" id="exemple1"><img src="https://tse3.mm.bing.net/th/id/OIP.AaajI7liZooIvenKB8LwJAHaEo?w=247&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7"  width="100%" height="auto" alt=""></div>
<div  class="exemple" id="exemple2"><img src="https://tse3.mm.bing.net/th/id/OIP.2L7My8fl6EmcOjiLdZ48XAHaEK?w=280&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7"  width="100%" height="auto" alt=""></div>
<div class="exemple" id="exemple3"><img src="https://tse4.mm.bing.net/th/id/OIP.P0hq2u7jo_o3Txegm7O1rAHaEo?w=237&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7"  width="100%" height="auto" alt=""></div>
</div>
<div class="colone">
  <h3 id="fr"> Merco 10 pro max cacheté venus de londre <br>prix: 150.000 €</h3>
  <h3 id="fr">Merco 11 pro cacheté venus de chine <br>prix: 175.000 €</h3>
  <h3 id="fr">Merco 11 pro max cacheté venus de Niger <br>prix: 190.000 €</h3>
</div>

<div>
  <div  class="exemple" id="exemple1"><img src="https://tse3.mm.bing.net/th/id/OIP.ZtEmezEUwX3cxcDWQY1wRgHaEc?w=257&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7"  width="95%" height="auto" alt=""></div>
  <div  class="exemple" id="exemple2"><img src="https://tse4.mm.bing.net/th/id/OIP.mQHzBN3bzNSwpP5_3pUmkgHaEK?w=307&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7"  width="95%" height="auto" alt=""></div>
  <div class="exemple" id="exemple3"><img src="https://tse4.mm.bing.net/th/id/OIP.xLaHAbShUIwpfIAfe0EmIwHaEd?pid=ImgDet&w=187&h=112&c=7&dpr=1.3"   width="150%" height="auto" alt=""></div>
  </div>
  <div class="colone">
    <h3 id="fr">Merco 12 cacheté venus du Burkina <br>prix: 200.000 €</h3>
    <h3 id="fr">Merco 12 pro cacheté venus de France <br>prix: 250.000 €</h3>
    <h3 id="fr">Merco 14 pro max cacheté venus de côte d'ivoire <br>prix: 5.000.000 €</h3>
  </div>
  <br>
  <br>
  <br>
  <center><div> 
    <iframe width="420" height="315"
    src="https://www.youtube.com/embed/FYuy_dOtek8" >
    </iframe>
  
  </div></center>
  <br>
  <center><div class="ut"><h1>Inscrivez-vous !</h1></div>
<form action="">
  <label for="Utilisateur" class="utt">Nom:</label>
  <input type="text" id="Utilisateur" name="Nom" placeholder="entrez votre nom ..." /> <br>
  <br>
  <label for="Utilisateur" class="utt">Prenom :</label>
  <input type="text" id="Utilisateur" name="Nom" placeholder="entrez votre prenom ..." /><br>
  <br>
  <label for="Utilisateur" class="utt">Password :</label>
  <input type="text" id="Utilisateur" name="Nom" placeholder="entrez votre code ..." /><br>
  <br>
  <label for="Utilisateur" class="utt">Contact :</label>
  <input type="text" id="Utilisateur" name="Nom" placeholder="entrez votre contact ..." /><br>
  <br>
  <button class="bl">envoyer</button></center>
  <br>
  <br>
  <footer class="pied">
 <div class="colonne">
  <div>
  <h2>PRIX DU NOEUF</h2>
  <ol type="#" class="ab">
      <li>Marques</li>
      <li>Concessionnaires</li>
      <li>Comparateur</li>
  </ol>
</div>
<div>
    <h2>OCCASION</h2>
    <ol class="ab">
        <li>Recherce</li>
        <li>Annonces du jour</li>
        <li>Vendeur pro</li>
    </ol>
  </div>
<div>
      <h2>AUTO MAG</h2>
      <ol class="ab">
          <li>Nouveautés</li>
          <li>Actu</li>
          <li>Essais</li>
          <li>Concepts</li>
      </ol>
    </div>
</div> 
<br>
<br>
<br>
<div class="colonne">
  <div>
  <h2>GUIDE PRATIQUE</h2>
  <ol type="#" class="ab">
      <li>Droits de douane</li>
      <li>FCR</li>
      <li>Permi de conduite</li>
      <li>Visite technique</li>
      <li>Vignette</li>
      <li>Voiture populaire</li>
  </ol>
</div>
<div>
  <h2>MON ESPACE</h2>
  <ol type="#" class="ab">
      <li>Créer une annonce</li>
      <li>Annonces favorite</li>
      <li>Gérer mes alertes</li>
      <li>Inscription</li>
      <li>Gérer mes informations</li>
      <li>Mes Annonces</li>
  </ol>
</div>
<div>
  <h2>QUI SOMME-NOUS ?</h2>
  <ol type="#" class="ab">
      <li>Contactez-nous</li>
      <li>Mention légales</li>
      <li>Politique de confidentialité</li>
      <li>Revue de presse</li>
      
  </ol>
</div>
</div>

</form>
</body>
</html>


