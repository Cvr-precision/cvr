
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CVR PRECISION | Rachat de matériel industriel d'occasion</title>

<meta name="description" content="CVR PRECISION rachète vos machines industrielles, machines-outils, équipements professionnels et matériels industriels d'occasion partout en France. Estimation rapide sur photos.">
<meta name="keywords" content="rachat machine outil, machines industrielles occasion, centre usinage occasion, matériel industriel occasion, rachat équipement industriel">
<meta name="author" content="CVR PRECISION">

<meta name="robots" content="index, follow">
<meta name="theme-color" content="#08111f">

<link rel="canonical" href="https://cvrprecision.fr/">

<meta property="og:title" content="CVR PRECISION - Rachat de matériel industriel d'occasion">
<meta property="og:description" content="Nous rachetons votre matériel industriel d'occasion rapidement et simplement.">
<meta property="og:type" content="website">
<meta property="og:image" content="logo.png">

<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="CVR PRECISION">
<meta name="twitter:description" content="Rachat de matériel industriel d'occasion.">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>

:root{
--black:#05080d;
--dark:#0b111b;
--dark2:#111827;
--steel:#334155;
--white:#ffffff;
--gray:#94a3b8;
--blue:#008cff;
--blue2:#00c6ff;
--glass:rgba(255,255,255,.08);
--border:rgba(255,255,255,.12);
--shadow:0 20px 60px rgba(0,0,0,.45);
--radius:22px;
--transition:.35s ease;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

html{
overflow-x:hidden;
}

body{
font-family:'Inter',Arial,sans-serif;
background:
radial-gradient(circle at 20% 10%,rgba(0,140,255,.15),transparent 35%),
radial-gradient(circle at 80% 30%,rgba(0,198,255,.12),transparent 35%),
var(--black);
color:var(--white);
overflow-x:hidden;
}

a{
color:inherit;
text-decoration:none;
}

img{
max-width:100%;
display:block;
}

section{
position:relative;
padding:100px 7%;
}

.container{
max-width:1400px;
margin:auto;
}

::-webkit-scrollbar{
width:10px;
}

::-webkit-scrollbar-track{
background:#05080d;
}

::-webkit-scrollbar-thumb{
background:linear-gradient(var(--blue),var(--blue2));
border-radius:20px;
}


/* PRELOADER */

.loader{
position:fixed;
inset:0;
background:#05080d;
display:flex;
align-items:center;
justify-content:center;
z-index:9999;
transition:opacity .6s ease,visibility .6s ease;
}

.loader.hide{
opacity:0;
visibility:hidden;
}

.loader span{
width:70px;
height:70px;
border-radius:50%;
border:4px solid rgba(255,255,255,.1);
border-top-color:var(--blue);
animation:spin 1s linear infinite;
}

@keyframes spin{
to{
transform:rotate(360deg);
}
}


/* HEADER */

header{
position:fixed;
top:0;
left:0;
width:100%;
z-index:1000;
padding:25px 7%;
transition:.4s ease;
}

header.scrolled{
background:rgba(5,8,13,.75);
backdrop-filter:blur(18px);
box-shadow:0 10px 40px rgba(0,0,0,.4);
padding:15px 7%;
}

.navbar{
display:flex;
align-items:center;
justify-content:space-between;
max-width:1400px;
margin:auto;
}

.logo img{
width:170px;
height:auto;
}

.nav-links{
display:flex;
gap:35px;
align-items:center;
}

.nav-links a{
font-size:15px;
font-weight:500;
position:relative;
}

.nav-links a::after{
content:"";
position:absolute;
bottom:-8px;
left:0;
width:0;
height:2px;
background:var(--blue);
transition:.3s;
}

.nav-links a:hover::after{
width:100%;
}

.menu-btn{
display:none;
font-size:28px;
cursor:pointer;
}


/* HERO */

.hero{
min-height:100vh;
display:flex;
align-items:center;
padding-top:120px;
overflow:hidden;
}

.hero::before{
content:"";
position:absolute;
width:600px;
height:600px;
right:-200px;
top:100px;
background:radial-gradient(circle,var(--blue),transparent 65%);
filter:blur(80px);
opacity:.35;
}

.hero-content{
max-width:900px;
position:relative;
z-index:2;
}

.hero h1{
font-size:clamp(2.8rem,6vw,5.8rem);
line-height:1.05;
font-weight:900;
letter-spacing:-3px;
margin-bottom:25px;
}

.hero h1 span{
background:linear-gradient(90deg,var(--blue),var(--blue2));
-webkit-background-clip:text;
color:transparent;
}

.hero p{
font-size:clamp(1.1rem,2vw,1.4rem);
color:#cbd5e1;
max-width:750px;
line-height:1.7;
margin-bottom:45px;
}

.hero-buttons{
display:flex;
gap:20px;
flex-wrap:wrap;
}

.btn{
padding:17px 35px;
border-radius:50px;
font-weight:700;
display:inline-flex;
align-items:center;
gap:12px;
transition:var(--transition);
}

.btn-primary{
background:linear-gradient(90deg,var(--blue),var(--blue2));
box-shadow:0 0 35px rgba(0,140,255,.45);
}

.btn-primary:hover{
transform:translateY(-5px);
box-shadow:0 0 60px rgba(0,140,255,.7);
}

.btn-outline{
border:1px solid rgba(255,255,255,.3);
background:rgba(255,255,255,.05);
backdrop-filter:blur(10px);
}

.btn-outline:hover{
background:white;
color:#000;
transform:translateY(-5px);
}


.hero-image{
position:absolute;
right:5%;
bottom:0;
width:45%;
opacity:.85;
z-index:1;
}

.hero-image img{
border-radius:30px;
box-shadow:var(--shadow);
}


/* TITRES */

.section-title{
text-align:center;
margin-bottom:70px;
}

.section-title h2{
font-size:clamp(2rem,4vw,3.5rem);
font-weight:800;
margin-bottom:15px;
}

.section-title p{
color:var(--gray);
font-size:1.1rem;
}

.reveal{
opacity:0;
transform:translateY(40px);
transition:.8s ease;
}

.reveal.active{
opacity:1;
transform:none;
}

</style>

</head>

<body>

<div class="loader">
<span></span>
</div>

<header>
<div class="navbar">

<a class="logo" href="#">
<img src="logo.png" alt="CVR PRECISION">
</a>

<nav class="nav-links">
<a href="#accueil">Accueil</a>
<a href="#presentation">Présentation</a>
<a href="#rachat">Nous rachetons</a>
<a href="#services">Prestations</a>
<a href="#contact">Contact</a>
</nav>

<div class="menu-btn">
<i class="fa-solid fa-bars"></i>
</div>

</div>
</header>

<main>

<section class="hero" id="accueil">

<div class="hero-content reveal">

<h1>
Nous rachetons votre
<span>matériel industriel</span>
d'occasion
</h1>

<p>
Une solution rapide, simple et sécurisée pour valoriser vos équipements industriels.
</p>

<div class="hero-buttons">

<a href="#contact" class="btn btn-primary">
<i class="fa-solid fa-file-invoice"></i>
Demander une estimation
</a>

<a href="#contact" class="btn btn-outline">
<i class="fa-solid fa-phone"></i>
Nous contacter
</a>

</div>

</div>

<div class="hero-image">
<img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&fit=crop&w=1200&q=80" alt="Machine industrielle">
</div>

</section>
<!-- PARTIE 2/10 -->

<section id="presentation">

<div class="container">

<div class="section-title reveal">
<h2>Présentation de <span style="color:#008cff">CVR PRECISION</span></h2>
<p>Une expertise dédiée au matériel industriel professionnel.</p>
</div>


<div class="presentation-grid">


<div class="presentation-text reveal">

<p>
Dans le cadre de notre activité, nous recherchons régulièrement du matériel professionnel et industriel d'occasion, à l'unité ou en lot.
</p>

<p>
Vous disposez d'équipements inutilisés, remplacés, en surplus, en arrêt de production ou destinés à la réforme ?
</p>

<p>
CVR PRECISION peut vous proposer une estimation rapide à partir de simples photos et informations.
</p>

<p>
Nous intervenons auprès des entreprises industrielles, ateliers de production, professionnels de la mécanique, fabricants et exploitants partout en France.
</p>


<a href="#contact" class="btn btn-primary">
<i class="fa-solid fa-camera"></i>
Envoyer vos équipements
</a>


</div>



<div class="presentation-card reveal">

<div class="glass-card">

<i class="fa-solid fa-industry"></i>

<h3>Expert industriel</h3>

<p>
Rachat, valorisation et enlèvement de matériels professionnels directement auprès des entreprises.
</p>

</div>


<div class="glass-card">

<i class="fa-solid fa-truck-fast"></i>

<h3>Intervention nationale</h3>

<p>
Organisation complète du démontage, chargement et transport.
</p>

</div>


</div>


</div>

</div>

</section>




<section id="rachat">


<div class="container">


<div class="section-title reveal">

<h2>Nous rachetons</h2>

<p>
Une large gamme de matériels industriels.
</p>

</div>



<div class="equipment-grid">



<div class="equipment-card reveal">
<i class="fa-solid fa-gears"></i>
<h3>Machines-outils</h3>
<p>Centres d'usinage, tours CNC, fraiseuses et équipements industriels.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-bolt"></i>
<h3>Groupes électrogènes</h3>
<p>Groupes de secours, générateurs industriels et équipements énergétiques.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-tree"></i>
<h3>Machines à bois</h3>
<p>Machines professionnelles pour l'industrie du bois.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-industry"></i>
<h3>Machines aluminium</h3>
<p>Équipements de fabrication aluminium et production industrielle.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-dolly"></i>
<h3>Manutention</h3>
<p>Chariots élévateurs, matériels de levage et équipements logistiques.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-truck-monster"></i>
<h3>Engins de chantier</h3>
<p>Matériels TP, véhicules industriels et équipements lourds.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-car"></i>
<h3>Véhicules professionnels</h3>
<p>Utilitaires, poids lourds et véhicules d'entreprise.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-scissors"></i>
<h3>Outils coupants</h3>
<p>Carbure, porte-outils et stocks industriels.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-industry"></i>
<h3>Lignes de production</h3>
<p>Machines complètes et équipements de production.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-boxes-stacked"></i>
<h3>Stocks industriels</h3>
<p>Surplus, composants et matériels inutilisés.</p>
</div>


<div class="equipment-card reveal">
<i class="fa-solid fa-layer-group"></i>
<h3>Tous matériels industriels</h3>
<p>Nous étudions toutes propositions.</p>
</div>


</div>


</div>


</section>





<style>


.presentation-grid{

display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
align-items:center;

}


.presentation-text p{

color:#cbd5e1;
font-size:1.1rem;
line-height:1.8;
margin-bottom:22px;

}



.presentation-card{

display:grid;
gap:25px;

}



.glass-card{


background:
linear-gradient(
145deg,
rgba(255,255,255,.12),
rgba(255,255,255,.03)
);

border:1px solid var(--border);

padding:35px;

border-radius:var(--radius);

backdrop-filter:blur(20px);

box-shadow:var(--shadow);

transition:.4s;


}


.glass-card:hover{

transform:translateY(-10px);

border-color:rgba(0,140,255,.5);

}



.glass-card i{

font-size:40px;

color:var(--blue);

margin-bottom:20px;

}



.glass-card h3{

font-size:1.5rem;

margin-bottom:12px;

}



.glass-card p{

color:var(--gray);

line-height:1.7;

}




.equipment-grid{

display:grid;

grid-template-columns:repeat(4,1fr);

gap:25px;

}



.equipment-card{


background:
linear-gradient(
145deg,
rgba(255,255,255,.08),
rgba(255,255,255,.02)
);


border:1px solid var(--border);

border-radius:var(--radius);

padding:35px 25px;

text-align:center;

transition:.4s;

backdrop-filter:blur(15px);


}



.equipment-card:hover{

transform:translateY(-12px);

box-shadow:
0 20px 50px rgba(0,140,255,.18);

border-color:var(--blue);

}



.equipment-card i{

font-size:38px;

color:var(--blue);

margin-bottom:20px;

transition:.3s;

}



.equipment-card:hover i{

transform:scale(1.15);

}



.equipment-card h3{

font-size:1.15rem;

margin-bottom:15px;

}



.equipment-card p{

color:var(--gray);

font-size:.95rem;

line-height:1.6;

}



@media(max-width:1100px){

.equipment-grid{

grid-template-columns:repeat(3,1fr);

}


.presentation-grid{

grid-template-columns:1fr;

}

.hero-image{

opacity:.25;

width:80%;

}

}



@media(max-width:768px){


.nav-links{

position:fixed;

top:0;

right:-100%;

width:280px;

height:100vh;

background:#070b12;

flex-direction:column;

justify-content:center;

transition:.4s;

box-shadow:-20px 0 50px rgba(0,0,0,.5);

}


.nav-links.active{

right:0;

}


.menu-btn{

display:block;

}



.equipment-grid{

grid-template-columns:1fr;

}


section{

padding:80px 5%;

}


.hero h1{

letter-spacing:-1px;

}


.hero-image{

display:none;

}


}

</style>
<!-- PARTIE 3/10 -->

<section id="services">

<div class="container">


<div class="section-title reveal">

<h2>Nos prestations</h2>

<p>
Une prise en charge complète de vos équipements industriels.
</p>

</div>



<div class="services-grid">



<div class="service-card reveal">

<i class="fa-solid fa-camera"></i>

<h3>Estimation sur photos</h3>

<p>
Envoyez-nous simplement des photos et les informations disponibles. Notre équipe réalise une première analyse rapidement.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-chart-line"></i>

<h3>Valorisation rapide</h3>

<p>
Nous trouvons la meilleure solution pour donner une seconde vie à vos équipements professionnels.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-screwdriver-wrench"></i>

<h3>Achat en l'état</h3>

<p>
Nous achetons les machines dans leur état actuel, même avec des défauts ou nécessitant une remise en service.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-ban"></i>

<h3>Aucune garantie demandée</h3>

<p>
Une solution simple adaptée aux entreprises souhaitant libérer rapidement leur espace industriel.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-map-location-dot"></i>

<h3>Déplacement national</h3>

<p>
Nous intervenons partout en France pour récupérer vos équipements.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-warehouse"></i>

<h3>Sortie d'usine</h3>

<p>
Organisation complète de la récupération depuis votre site industriel.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-truck"></i>

<h3>Chargement et transport</h3>

<p>
Nos solutions comprennent la manutention et l'organisation du transport adapté.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-file-invoice"></i>

<h3>Transport CMR</h3>

<p>
Gestion professionnelle des opérations de transport avec documents adaptés.
</p>

</div>




<div class="service-card reveal">

<i class="fa-solid fa-money-bill-transfer"></i>

<h3>Paiement intégral</h3>

<p>
Le règlement est effectué avant l'enlèvement du matériel selon les modalités convenues.
</p>

</div>




</div>


</div>

</section>




<section id="avantages">


<div class="container">


<div class="section-title reveal">

<h2>Pourquoi choisir CVR PRECISION</h2>

<p>
Un partenaire fiable pour vos équipements industriels.
</p>

</div>



<div class="advantages-grid">



<div class="advantage-card reveal">

<div class="number">
01
</div>

<i class="fa-solid fa-bolt"></i>

<h3>Réactivité</h3>

<p>
Une réponse rapide pour étudier vos propositions et avancer efficacement.
</p>

</div>



<div class="advantage-card reveal">

<div class="number">
02
</div>

<i class="fa-solid fa-user-tie"></i>

<h3>Professionnalisme</h3>

<p>
Une approche adaptée aux contraintes des entreprises industrielles.
</p>

</div>



<div class="advantage-card reveal">

<div class="number">
03
</div>

<i class="fa-solid fa-shield-halved"></i>

<h3>Paiement sécurisé</h3>

<p>
Des transactions claires et sécurisées avant enlèvement.
</p>

</div>



<div class="advantage-card reveal">

<div class="number">
04
</div>

<i class="fa-solid fa-clock"></i>

<h3>Rapidité</h3>

<p>
Une organisation efficace pour réduire les délais.
</p>

</div>



<div class="advantage-card reveal">

<div class="number">
05
</div>

<i class="fa-solid fa-handshake"></i>

<h3>Accompagnement</h3>

<p>
Un interlocuteur unique pour suivre votre projet.
</p>

</div>



<div class="advantage-card reveal">

<div class="number">
06
</div>

<i class="fa-solid fa-earth-europe"></i>

<h3>Intervention nationale</h3>

<p>
Une présence auprès des professionnels partout en France.
</p>

</div>


</div>


</div>


</section>




<section id="chiffres">


<div class="container">


<div class="stats-grid">



<div class="stat-card reveal">

<i class="fa-solid fa-industry"></i>

<strong class="counter" data-target="500">0</strong>

<span>Matériels étudiés</span>

</div>



<div class="stat-card reveal">

<i class="fa-solid fa-location-dot"></i>

<strong class="counter" data-target="100">0</strong>

<span>Déplacements réalisés</span>

</div>



<div class="stat-card reveal">

<i class="fa-solid fa-users"></i>

<strong class="counter" data-target="15">0</strong>

<span>Années d'expérience</span>

</div>



<div class="stat-card reveal">

<i class="fa-solid fa-truck-fast"></i>

<strong class="counter" data-target="48">0</strong>

<span>Heures pour une première réponse</span>

</div>



</div>


</div>


</section>




<style>


.services-grid{

display:grid;

grid-template-columns:repeat(3,1fr);

gap:25px;

}



.service-card{

background:
linear-gradient(
145deg,
rgba(255,255,255,.1),
rgba(255,255,255,.03)
);

border:1px solid var(--border);

padding:35px;

border-radius:var(--radius);

transition:.4s;

backdrop-filter:blur(15px);

}



.service-card:hover{

transform:translateY(-10px);

border-color:var(--blue);

box-shadow:0 20px 50px rgba(0,140,255,.2);

}



.service-card i{

font-size:40px;

color:var(--blue);

margin-bottom:25px;

}



.service-card h3{

font-size:1.3rem;

margin-bottom:15px;

}



.service-card p{

color:var(--gray);

line-height:1.7;

}





.advantages-grid{

display:grid;

grid-template-columns:repeat(3,1fr);

gap:30px;

}



.advantage-card{

position:relative;

padding:40px 30px;

background:rgba(255,255,255,.05);

border:1px solid var(--border);

border-radius:var(--radius);

overflow:hidden;

transition:.4s;

}



.advantage-card:hover{

transform:translateY(-10px);

}



.advantage-card .number{

position:absolute;

right:20px;

top:10px;

font-size:80px;

font-weight:900;

color:rgba(255,255,255,.04);

}



.advantage-card i{

font-size:40px;

color:var(--blue);

margin-bottom:20px;

}



.advantage-card h3{

margin-bottom:15px;

}



.advantage-card p{

color:var(--gray);

line-height:1.7;

}





.stats-grid{

display:grid;

grid-template-columns:repeat(4,1fr);

gap:25px;

}



.stat-card{

text-align:center;

padding:45px 20px;

background:
linear-gradient(
145deg,
rgba(255,255,255,.08),
rgba(255,255,255,.02)
);

border:1px solid var(--border);

border-radius:var(--radius);

}



.stat-card i{

font-size:40px;

color:var(--blue);

margin-bottom:20px;

}



.stat-card strong{

display:block;

font-size:3rem;

font-weight:900;

}



.stat-card span{

color:var(--gray);

}



@media(max-width:1000px){

.services-grid,
.advantages-grid{

grid-template-columns:1fr 1fr;

}


.stats-grid{

grid-template-columns:1fr 1fr;

}

}



@media(max-width:650px){

.services-grid,
.advantages-grid,
.stats-grid{

grid-template-columns:1fr;

}

}

</style>
<!-- PARTIE 4/10 -->

<section id="methode">

<div class="container">


<div class="section-title reveal">

<h2>Notre méthode</h2>

<p>
Un processus simple, rapide et transparent.
</p>

</div>



<div class="timeline">



<div class="timeline-item reveal">

<div class="timeline-icon">
<i class="fa-solid fa-camera"></i>
</div>

<div class="timeline-content">

<h3>1. Envoi des informations</h3>

<p>
Vous nous transmettez les photos, références machines, années, caractéristiques techniques et informations disponibles.
</p>

</div>

</div>




<div class="timeline-item reveal">

<div class="timeline-icon">
<i class="fa-solid fa-magnifying-glass-chart"></i>
</div>

<div class="timeline-content">

<h3>2. Étude et estimation</h3>

<p>
Notre équipe analyse votre matériel afin de déterminer une proposition adaptée au marché.
</p>

</div>

</div>




<div class="timeline-item reveal">

<div class="timeline-icon">
<i class="fa-solid fa-file-signature"></i>
</div>

<div class="timeline-content">

<h3>3. Validation de l'offre</h3>

<p>
Après accord, nous organisons ensemble les modalités d'enlèvement.
</p>

</div>

</div>




<div class="timeline-item reveal">

<div class="timeline-icon">
<i class="fa-solid fa-truck-ramp-box"></i>
</div>

<div class="timeline-content">

<h3>4. Enlèvement du matériel</h3>

<p>
Nous organisons la sortie, la manutention et le transport de vos équipements.
</p>

</div>

</div>




<div class="timeline-item reveal">

<div class="timeline-icon">
<i class="fa-solid fa-euro-sign"></i>
</div>

<div class="timeline-content">

<h3>5. Paiement</h3>

<p>
Le règlement est effectué selon les conditions définies avant l'enlèvement.
</p>

</div>

</div>



</div>


</div>

</section>






<section id="galerie">


<div class="container">


<div class="section-title reveal">

<h2>Nos équipements industriels</h2>

<p>
Quelques exemples d'univers industriels.
</p>

</div>




<div class="gallery-grid">



<div class="gallery-item reveal">

<img loading="lazy" 
src="https://images.unsplash.com/photo-1565439396051-7f5f3e1b7c3c?auto=format&fit=crop&w=900&q=80"
alt="Centre d'usinage industriel">

</div>




<div class="gallery-item reveal">

<img loading="lazy"
src="https://images.unsplash.com/photo-1581092160607-ee22621dd758?auto=format&fit=crop&w=900&q=80"
alt="Atelier industriel">

</div>




<div class="gallery-item reveal">

<img loading="lazy"
src="https://images.unsplash.com/photo-1565793298595-6a879b1d9492?auto=format&fit=crop&w=900&q=80"
alt="Production industrielle">

</div>




<div class="gallery-item reveal">

<img loading="lazy"
src="https://images.unsplash.com/photo-1504917595217-d4dc5ebe6122?auto=format&fit=crop&w=900&q=80"
alt="Maintenance industrielle">

</div>




<div class="gallery-item reveal">

<img loading="lazy"
src="https://images.unsplash.com/photo-1581092334651-ddf26d9a09d0?auto=format&fit=crop&w=900&q=80"
alt="Machines professionnelles">

</div>




<div class="gallery-item reveal">

<img loading="lazy"
src="https://images.unsplash.com/photo-1537462716453-77307d2f9c8c?auto=format&fit=crop&w=900&q=80"
alt="Industrie mécanique">

</div>



</div>



</div>


</section>





<div class="lightbox">

<button class="close-lightbox">
<i class="fa-solid fa-xmark"></i>
</button>

<img src="" alt="Image industrielle agrandie">

</div>





<style>



.timeline{

position:relative;

max-width:900px;

margin:auto;

}



.timeline::before{

content:"";

position:absolute;

left:50%;

top:0;

bottom:0;

width:2px;

background:linear-gradient(
var(--blue),
transparent
);

transform:translateX(-50%);

}



.timeline-item{

display:flex;

justify-content:space-between;

align-items:center;

margin-bottom:70px;

position:relative;

}



.timeline-icon{

width:70px;

height:70px;

border-radius:50%;

background:linear-gradient(
135deg,
var(--blue),
var(--blue2)
);

display:flex;

align-items:center;

justify-content:center;

font-size:28px;

position:absolute;

left:50%;

transform:translateX(-50%);

box-shadow:0 0 35px rgba(0,140,255,.5);

}



.timeline-content{

width:42%;

background:rgba(255,255,255,.06);

border:1px solid var(--border);

padding:30px;

border-radius:var(--radius);

backdrop-filter:blur(15px);

}



.timeline-content h3{

margin-bottom:15px;

}



.timeline-content p{

color:var(--gray);

line-height:1.7;

}



.timeline-item:nth-child(even){

flex-direction:row-reverse;

}





.gallery-grid{

display:grid;

grid-template-columns:repeat(3,1fr);

gap:25px;

}



.gallery-item{

height:280px;

overflow:hidden;

border-radius:var(--radius);

border:1px solid var(--border);

cursor:pointer;

}



.gallery-item img{

width:100%;

height:100%;

object-fit:cover;

transition:.6s;

}



.gallery-item:hover img{

transform:scale(1.12);

}



.lightbox{

position:fixed;

inset:0;

background:rgba(0,0,0,.9);

display:flex;

align-items:center;

justify-content:center;

z-index:5000;

opacity:0;

visibility:hidden;

transition:.4s;

}



.lightbox.active{

opacity:1;

visibility:visible;

}



.lightbox img{

max-width:90%;

max-height:85%;

border-radius:20px;

box-shadow:0 20px 80px black;

}



.close-lightbox{

position:absolute;

top:30px;

right:40px;

font-size:35px;

background:none;

border:0;

color:white;

cursor:pointer;

}



@media(max-width:900px){


.timeline::before{

left:35px;

}


.timeline-item,
.timeline-item:nth-child(even){

display:block;

padding-left:90px;

}



.timeline-icon{

left:35px;

}



.timeline-content{

width:100%;

}



.gallery-grid{

grid-template-columns:1fr;

}


}

</style>
<!-- PARTIE 5/10 -->

<section id="contact">

<div class="container">


<div class="section-title reveal">

<h2>Contactez CVR PRECISION</h2>

<p>
Une question, une machine à vendre ou un projet industriel ?
</p>

</div>




<div class="contact-grid">



<div class="contact-info reveal">


<div class="contact-card">

<i class="fa-solid fa-building"></i>

<div>

<h3>Entreprise</h3>

<p>CVR PRECISION</p>

</div>

</div>




<div class="contact-card">

<i class="fa-solid fa-user"></i>

<div>

<h3>Votre interlocuteur</h3>

<p>Eric</p>

</div>

</div>




<div class="contact-card">

<i class="fa-solid fa-phone"></i>

<div>

<h3>Téléphone</h3>

<p>
<a href="tel:+33695527388">
+33 6 95 52 73 88
</a>
</p>

<a class="small-btn" href="tel:+33695527388">
Appeler
</a>

</div>

</div>




<div class="contact-card">

<i class="fa-solid fa-envelope"></i>

<div>

<h3>Email</h3>

<p>
<a href="mailto:cvr.precision@gmail.com">
cvr.precision@gmail.com
</a>
</p>

<a class="small-btn" href="mailto:cvr.precision@gmail.com">
Envoyer un email
</a>

</div>

</div>




<div class="contact-card">

<i class="fa-solid fa-location-dot"></i>

<div>

<h3>Adresse</h3>

<p>
131 Boulevard Carnot<br>
78110 Le Vésinet
</p>

</div>

</div>



</div>





<div class="contact-form reveal">


<form>


<div class="form-group">

<label for="nom">
Nom
</label>

<input 
id="nom"
type="text"
placeholder="Votre nom"
required>

</div>




<div class="form-group">

<label for="entreprise">
Entreprise
</label>

<input 
id="entreprise"
type="text"
placeholder="Votre entreprise">

</div>




<div class="form-group">

<label for="telephone">
Téléphone
</label>

<input 
id="telephone"
type="tel"
placeholder="Votre téléphone">

</div>




<div class="form-group">

<label for="email">
Email
</label>

<input 
id="email"
type="email"
placeholder="Votre email"
required>

</div>




<div class="form-group">

<label for="message">
Message
</label>

<textarea
id="message"
rows="5"
placeholder="Décrivez votre matériel"></textarea>

</div>



<button type="submit" class="btn btn-primary">

<i class="fa-solid fa-paper-plane"></i>

Envoyer la demande

</button>



</form>


</div>


</div>




<div class="map-container reveal">

<iframe
src="https://maps.google.com/maps?q=131%20Boulevard%20Carnot%2078110%20Le%20V%C3%A9sinet&t=&z=15&ie=UTF8&iwloc=&output=embed"
loading="lazy"
allowfullscreen=""
title="Localisation CVR PRECISION">
</iframe>

</div>


</div>


</section>






<footer>


<div class="container">


<div class="footer-grid">



<div class="footer-brand">


<img src="logo.png" alt="CVR PRECISION">


<p>
Rachat et valorisation de matériels industriels d'occasion partout en France.
</p>


<div class="socials">


<a href="#">
<i class="fa-brands fa-linkedin-in"></i>
</a>


<a href="#">
<i class="fa-brands fa-facebook-f"></i>
</a>


<a href="#">
<i class="fa-brands fa-instagram"></i>
</a>


</div>


</div>





<div class="footer-links">


<h3>Navigation</h3>

<a href="#accueil">Accueil</a>

<a href="#presentation">Présentation</a>

<a href="#rachat">Matériels</a>

<a href="#services">Prestations</a>

<a href="#contact">Contact</a>


</div>





<div class="footer-contact">


<h3>Coordonnées</h3>


<p>
<i class="fa-solid fa-phone"></i>
+33 6 95 52 73 88
</p>


<p>
<i class="fa-solid fa-envelope"></i>
cvr.precision@gmail.com
</p>


<p>
<i class="fa-solid fa-location-dot"></i>
Le Vésinet, France
</p>


</div>



</div>





<div class="footer-bottom">


<p>
© 2026 CVR PRECISION - Tous droits réservés.
</p>


</div>



</div>


</footer>





<button class="top-btn">

<i class="fa-solid fa-arrow-up"></i>

</button>





<style>



.contact-grid{

display:grid;

grid-template-columns:1fr 1fr;

gap:50px;

}



.contact-card{

display:flex;

gap:25px;

align-items:flex-start;

padding:25px;

margin-bottom:20px;

background:rgba(255,255,255,.06);

border:1px solid var(--border);

border-radius:20px;

}



.contact-card i{

font-size:30px;

color:var(--blue);

}



.contact-card h3{

margin-bottom:8px;

}



.contact-card p{

color:var(--gray);

line-height:1.6;

}



.small-btn{

display:inline-block;

margin-top:10px;

padding:8px 18px;

border-radius:30px;

background:rgba(0,140,255,.15);

color:#fff;

font-size:.9rem;

}





.contact-form{

background:rgba(255,255,255,.06);

padding:40px;

border-radius:var(--radius);

border:1px solid var(--border);

backdrop-filter:blur(15px);

}



.form-group{

margin-bottom:20px;

}



.form-group label{

display:block;

margin-bottom:8px;

font-weight:600;

}



.form-group input,
.form-group textarea{


width:100%;

padding:15px 18px;

background:rgba(255,255,255,.08);

border:1px solid rgba(255,255,255,.15);

border-radius:15px;

color:white;

font-family:inherit;

}



.form-group input:focus,
.form-group textarea:focus{

outline:none;

border-color:var(--blue);

}





.map-container{

margin-top:60px;

height:400px;

overflow:hidden;

border-radius:25px;

border:1px solid var(--border);

}



.map-container iframe{

width:100%;

height:100%;

border:0;

}




footer{

background:#03050a;

padding:70px 7% 30px;

border-top:1px solid rgba(255,255,255,.1);

}



.footer-grid{

display:grid;

grid-template-columns:2fr 1fr 1fr;

gap:50px;

}



.footer-brand img{

width:180px;

margin-bottom:20px;

}



.footer-brand p{

color:var(--gray);

line-height:1.7;

}



.socials{

display:flex;

gap:15px;

margin-top:25px;

}



.socials a{

width:45px;

height:45px;

display:flex;

align-items:center;

justify-content:center;

background:rgba(255,255,255,.08);

border-radius:50%;

transition:.3s;

}



.socials a:hover{

background:var(--blue);

transform:translateY(-5px);

}



.footer-links,
.footer-contact{

display:flex;

flex-direction:column;

gap:15px;

}



.footer-links h3,
.footer-contact h3{

margin-bottom:15px;

}



.footer-contact p{

color:var(--gray);

}



.footer-bottom{

margin-top:50px;

padding-top:25px;

border-top:1px solid rgba(255,255,255,.1);

text-align:center;

color:var(--gray);

}



.top-btn{

position:fixed;

bottom:30px;

right:30px;

width:55px;

height:55px;

border-radius:50%;

border:0;

background:linear-gradient(
135deg,
var(--blue),
var(--blue2)
);

color:white;

font-size:20px;

cursor:pointer;

opacity:0;

visibility:hidden;

transition:.3s;

z-index:900;

}



.top-btn.active{

opacity:1;

visibility:visible;

}



@media(max-width:900px){

.contact-grid,
.footer-grid{

grid-template-columns:1fr;

}

}

</style>
<!-- PARTIE 6/10 -->

<script>

document.addEventListener("DOMContentLoaded",()=>{


/* PRELOADER */

const loader=document.querySelector(".loader");

setTimeout(()=>{

loader.classList.add("hide");

},800);




/* HEADER SCROLL */

const header=document.querySelector("header");

window.addEventListener("scroll",()=>{

if(window.scrollY>80){

header.classList.add("scrolled");

}else{

header.classList.remove("scrolled");

}

});





/* MENU MOBILE */

const menuBtn=document.querySelector(".menu-btn");

const nav=document.querySelector(".nav-links");

menuBtn.addEventListener("click",()=>{

nav.classList.toggle("active");

menuBtn.innerHTML=
nav.classList.contains("active")
?
'<i class="fa-solid fa-xmark"></i>'
:
'<i class="fa-solid fa-bars"></i>';

});



document.querySelectorAll(".nav-links a").forEach(link=>{

link.addEventListener("click",()=>{

nav.classList.remove("active");

menuBtn.innerHTML=
'<i class="fa-solid fa-bars"></i>';

});

});





/* ANIMATIONS SCROLL */

const observer=new IntersectionObserver((entries)=>{


entries.forEach(entry=>{


if(entry.isIntersecting){

entry.target.classList.add("active");

}

});


},
{

threshold:.15

});



document.querySelectorAll(".reveal").forEach(el=>{

observer.observe(el);

});







/* COMPTEURS */

const counters=document.querySelectorAll(".counter");


let started=false;


const counterObserver=new IntersectionObserver(entries=>{


entries.forEach(entry=>{


if(entry.isIntersecting && !started){


started=true;


counters.forEach(counter=>{


let target=parseInt(counter.dataset.target);

let current=0;

let increment=Math.ceil(target/80);



let timer=setInterval(()=>{


current+=increment;


if(current>=target){

counter.textContent=target;

clearInterval(timer);

}else{

counter.textContent=current;

}


},25);



});


}



});


},{threshold:.5});



const stats=document.querySelector("#chiffres");


if(stats){

counterObserver.observe(stats);

}







/* RETOUR EN HAUT */

const topBtn=document.querySelector(".top-btn");


window.addEventListener("scroll",()=>{


if(window.scrollY>500){

topBtn.classList.add("active");

}else{

topBtn.classList.remove("active");

}


});



topBtn.addEventListener("click",()=>{


window.scrollTo({

top:0,

behavior:"smooth"

});


});








/* LIGHTBOX GALERIE */


const galleryImages=document.querySelectorAll(".gallery-item img");

const lightbox=document.querySelector(".lightbox");

const lightboxImg=document.querySelector(".lightbox img");

const closeLightbox=document.querySelector(".close-lightbox");



galleryImages.forEach(image=>{


image.addEventListener("click",()=>{


lightboxImg.src=image.src;

lightboxImg.alt=image.alt;

lightbox.classList.add("active");


});


});



closeLightbox.addEventListener("click",()=>{


lightbox.classList.remove("active");


});



lightbox.addEventListener("click",(e)=>{


if(e.target===lightbox){

lightbox.classList.remove("active");

}


});







/* FORMULAIRE */

const form=document.querySelector("form");


form.addEventListener("submit",(e)=>{


e.preventDefault();


const button=form.querySelector("button");


button.innerHTML=
'<i class="fa-solid fa-check"></i> Demande envoyée';



button.style.background="#16a34a";


setTimeout(()=>{


form.reset();


button.innerHTML=
'<i class="fa-solid fa-paper-plane"></i> Envoyer la demande';


button.style.background="";


},3000);



});







/* EFFET LUMIERE SOURIS DESKTOP */


const hero=document.querySelector(".hero");


document.addEventListener("mousemove",(e)=>{


if(window.innerWidth>900){


let x=e.clientX/window.innerWidth*100;

let y=e.clientY/window.innerHeight*100;


hero.style.background=
`
radial-gradient(
circle at ${x}% ${y}%,
rgba(0,140,255,.12),
transparent 25%
)
`;

}


});






/* FERMETURE ESC LIGHTBOX */


document.addEventListener("keydown",(e)=>{


if(e.key==="Escape"){


lightbox.classList.remove("active");


}


});



});

</script>
<!-- PARTIE 7/10 -->

<script type="application/ld+json">

{
"@context":"https://schema.org",
"@type":"LocalBusiness",
"name":"CVR PRECISION",
"description":"Rachat de matériel industriel d'occasion, machines-outils, équipements professionnels et matériels industriels.",
"image":"logo.png",
"url":"https://cvrprecision.fr",
"telephone":"+33695527388",
"email":"cvr.precision@gmail.com",
"address":{
"@type":"PostalAddress",
"streetAddress":"131 Boulevard Carnot",
"postalCode":"78110",
"addressLocality":"Le Vésinet",
"addressCountry":"FR"
},
"areaServed":{
"@type":"Country",
"name":"France"
},
"priceRange":"€€",
"openingHours":"Mo-Fr 08:00-18:00"
}

</script>





<style>


/* SECTION METHODE */

#methode{

background:
linear-gradient(
180deg,
transparent,
rgba(0,140,255,.04),
transparent
);

}





/* EFFETS PREMIUM SUPPLEMENTAIRES */


section::before{

content:"";

position:absolute;

width:300px;

height:300px;

border-radius:50%;

background:rgba(0,140,255,.08);

filter:blur(100px);

z-index:-1;

}



section:nth-child(even)::before{

right:0;

}



section:nth-child(odd)::before{

left:0;

}





/* GLASS PREMIUM */

.glass-effect{


background:

linear-gradient(
135deg,
rgba(255,255,255,.12),
rgba(255,255,255,.02)
);

border:

1px solid rgba(255,255,255,.15);

box-shadow:

inset 0 1px 1px rgba(255,255,255,.15),

0 25px 70px rgba(0,0,0,.45);

backdrop-filter:

blur(25px);


}






/* SEPARATEURS INDUSTRIELS */


.industry-line{

height:1px;

width:100%;

background:

linear-gradient(
90deg,
transparent,
var(--blue),
transparent
);

margin:50px 0;

}





/* BOUTONS */


.btn{

position:relative;

overflow:hidden;

}



.btn::before{

content:"";

position:absolute;

top:0;

left:-100%;

width:100%;

height:100%;

background:

linear-gradient(
120deg,
transparent,
rgba(255,255,255,.35),
transparent
);

transition:.6s;

}



.btn:hover::before{

left:100%;

}





/* IMAGE HERO OPTIMISATION */


.hero-image img{

animation:

floating 8s ease-in-out infinite;

}



@keyframes floating{


0%,100%{

transform:translateY(0);

}


50%{

transform:translateY(-15px);

}


}







/* LOGO */


.logo img{

filter:

drop-shadow(
0 0 20px rgba(0,140,255,.25)
);

transition:.4s;

}



.logo img:hover{

transform:scale(1.05);

}





/* CURSEUR CUSTOM */


.cursor-dot{

position:fixed;

width:12px;

height:12px;

background:var(--blue);

border-radius:50%;

pointer-events:none;

z-index:99999;

transform:translate(-50%,-50%);

mix-blend-mode:screen;

display:none;

}



@media(min-width:1000px){


.cursor-dot{

display:block;

}


}




/* BARRE DE PROGRESSION */


.progress-bar{

position:fixed;

top:0;

left:0;

height:4px;

width:0;

background:

linear-gradient(
90deg,
var(--blue),
var(--blue2)
);

z-index:99999;

}





/* SECTION CONTACT */


#contact{

background:

radial-gradient(
circle at center,
rgba(0,140,255,.1),
transparent 45%
);

}





/* INPUTS */


input::placeholder,
textarea::placeholder{

color:#94a3b8;

}





/* FOOTER HOVER */


.footer-links a{

color:#cbd5e1;

transition:.3s;

}



.footer-links a:hover{

color:var(--blue);

padding-left:8px;

}





/* ACCESSIBILITE */


a:focus,
button:focus,
input:focus,
textarea:focus{

outline:2px solid var(--blue);

outline-offset:3px;

}





/* REDUCED MOTION */


@media(prefers-reduced-motion:reduce){


*,
*::before,
*::after{

animation:none!important;

transition:none!important;

scroll-behavior:auto!important;

}


}



</style>





<div class="progress-bar"></div>

<div class="cursor-dot"></div>




<script>


/* BARRE DE PROGRESSION */

const progress=document.querySelector(".progress-bar");


window.addEventListener("scroll",()=>{


let height=document.documentElement.scrollHeight-window.innerHeight;


let progressValue=(window.scrollY/height)*100;


progress.style.width=progressValue+"%";


});







/* CURSEUR */

const cursor=document.querySelector(".cursor-dot");


document.addEventListener("mousemove",(e)=>{


if(window.innerWidth>1000){


cursor.style.left=e.clientX+"px";

cursor.style.top=e.clientY+"px";


}


});





/* EFFET HOVER CURSEUR */


document.querySelectorAll("a,button,.equipment-card,.service-card").forEach(item=>{


item.addEventListener("mouseenter",()=>{


cursor.style.transform="translate(-50%,-50%) scale(2)";


});



item.addEventListener("mouseleave",()=>{


cursor.style.transform="translate(-50%,-50%) scale(1)";


});


});



</script>
<!-- PARTIE 8/10 -->

<section id="engagement">

<div class="container">


<div class="section-title reveal">

<h2>Notre engagement</h2>

<p>
Une approche professionnelle basée sur la confiance et la transparence.
</p>

</div>



<div class="engagement-grid">



<div class="engagement-card reveal">

<i class="fa-solid fa-recycle"></i>

<h3>Donner une seconde vie</h3>

<p>
Nous contribuons à la revalorisation des équipements industriels en favorisant leur réutilisation.
</p>

</div>




<div class="engagement-card reveal">

<i class="fa-solid fa-handshake-angle"></i>

<h3>Une relation durable</h3>

<p>
Nous privilégions des échanges simples, rapides et professionnels avec nos partenaires.
</p>

</div>




<div class="engagement-card reveal">

<i class="fa-solid fa-industry"></i>

<h3>Culture industrielle</h3>

<p>
Notre connaissance du secteur permet d'évaluer différents types d'équipements professionnels.
</p>

</div>



</div>


</div>


</section>












<style>


.engagement-grid{

display:grid;

grid-template-columns:repeat(3,1fr);

gap:30px;

}



.engagement-card{

padding:40px 30px;

background:

linear-gradient(
145deg,
rgba(255,255,255,.08),
rgba(255,255,255,.02)
);

border:1px solid var(--border);

border-radius:var(--radius);

text-align:center;

transition:.4s;

}



.engagement-card:hover{

transform:translateY(-10px);

border-color:var(--blue);

box-shadow:0 20px 60px rgba(0,140,255,.15);

}



.engagement-card i{

font-size:45px;

color:var(--blue);

margin-bottom:25px;

}



.engagement-card h3{

font-size:1.4rem;

margin-bottom:15px;

}



.engagement-card p{

color:var(--gray);

line-height:1.7;

}







.faq-container{

max-width:900px;

margin:auto;

}



.faq-item{

margin-bottom:20px;

background:rgba(255,255,255,.05);

border:1px solid var(--border);

border-radius:20px;

overflow:hidden;

}



.faq-question{

width:100%;

display:flex;

justify-content:space-between;

align-items:center;

padding:25px;

background:none;

border:0;

color:white;

font-size:1.1rem;

font-weight:700;

cursor:pointer;

text-align:left;

}



.faq-question i{

transition:.3s;

color:var(--blue);

}



.faq-item.active .faq-question i{

transform:rotate(180deg);

}



.faq-answer{

max-height:0;

overflow:hidden;

transition:max-height .4s ease;

}



.faq-answer p{

padding:0 25px 25px;

color:var(--gray);

line-height:1.7;

}




@media(max-width:900px){


.engagement-grid{

grid-template-columns:1fr;

}


}

</style>





<script>


/* FAQ ACCORDEON */


document.querySelectorAll(".faq-question").forEach(button=>{


button.addEventListener("click",()=>{


const item=button.parentElement;

const answer=item.querySelector(".faq-answer");


document.querySelectorAll(".faq-item").forEach(other=>{


if(other!==item){

other.classList.remove("active");

other.querySelector(".faq-answer").style.maxHeight=null;

}


});



item.classList.toggle("active");



if(item.classList.contains("active")){


answer.style.maxHeight=answer.scrollHeight+"px";


}else{


answer.style.maxHeight=null;


}



});


});



</script>
<!-- PARTIE 9/10 -->

<section id="cta">

<div class="container">


<div class="cta-box reveal">


<div class="cta-content">


<h2>
Vous avez du matériel industriel à valoriser ?
</h2>


<p>
Contactez CVR PRECISION dès aujourd'hui pour obtenir une première estimation.
</p>



<div class="hero-buttons">


<a href="tel:+33695527388" class="btn btn-primary">

<i class="fa-solid fa-phone"></i>

Appeler maintenant

</a>


<a href="mailto:cvr.precision@gmail.com" class="btn btn-outline">

<i class="fa-solid fa-envelope"></i>

Envoyer un email

</a>


</div>


</div>



</div>


</div>


</section>






<section id="mentions">


<div class="container">


<div class="legal-box reveal">


<h2>
Informations légales
</h2>


<p>
CVR PRECISION - Rachat et valorisation de matériels industriels d'occasion.
</p>


<p>
Les informations présentes sur ce site sont fournies à titre indicatif et peuvent évoluer.
</p>


<p>
Toute reproduction totale ou partielle du contenu du site sans autorisation préalable est interdite.
</p>


</div>


</div>


</section>







<style>


#cta{

padding-top:50px;

}



.cta-box{

position:relative;

overflow:hidden;

padding:80px 50px;

border-radius:35px;

background:

linear-gradient(
135deg,
rgba(0,140,255,.25),
rgba(0,198,255,.08)
);

border:1px solid rgba(255,255,255,.2);

text-align:center;

box-shadow:

0 30px 80px rgba(0,0,0,.4);

}



.cta-box::before{

content:"";

position:absolute;

width:400px;

height:400px;

background:

radial-gradient(
circle,
rgba(0,198,255,.4),
transparent 70%
);

top:-200px;

right:-150px;

filter:blur(40px);

}



.cta-content{

position:relative;

z-index:2;

}



.cta-content h2{

font-size:clamp(2rem,4vw,3.5rem);

margin-bottom:20px;

}



.cta-content p{

font-size:1.2rem;

color:#dbeafe;

margin-bottom:35px;

}




.legal-box{

background:rgba(255,255,255,.05);

border:1px solid var(--border);

border-radius:25px;

padding:40px;

}



.legal-box h2{

margin-bottom:20px;

}



.legal-box p{

color:var(--gray);

line-height:1.8;

margin-bottom:15px;

}



</style>







<script>


/* SMOOTH ANCHOR FIX */


document.querySelectorAll('a[href^="#"]').forEach(anchor=>{


anchor.addEventListener("click",function(e){


const target=document.querySelector(this.getAttribute("href"));


if(target){


e.preventDefault();


target.scrollIntoView({

behavior:"smooth",

block:"start"

});


}



});


});





/* IMAGE LAZY FALLBACK */


if("loading" in HTMLImageElement.prototype){


document.querySelectorAll("img").forEach(img=>{


img.loading="lazy";


});


}






/* ANIMATION DES CARTES AU PASSAGE SOURIS */


const cards=document.querySelectorAll(
".equipment-card,.service-card,.advantage-card,.engagement-card,.stat-card"
);



cards.forEach(card=>{


card.addEventListener("mousemove",(e)=>{


const rect=card.getBoundingClientRect();


const x=e.clientX-rect.left;

const y=e.clientY-rect.top;


const centerX=rect.width/2;

const centerY=rect.height/2;


const rotateX=(y-centerY)/25;

const rotateY=(centerX-x)/25;


card.style.transform=
`
perspective(800px)
rotateX(${rotateX}deg)
rotateY(${rotateY}deg)
translateY(-8px)
`;



});



card.addEventListener("mouseleave",()=>{


card.style.transform="";


});



});



</script>
<!-- PARTIE 10/10 -->

<script>


/* PROTECTION DES LIENS EMAIL ET TELEPHONE */

document.querySelectorAll('a[href^="mailto:"], a[href^="tel:"]').forEach(link=>{


link.addEventListener("mouseenter",()=>{

link.style.opacity="0.75";

});


link.addEventListener("mouseleave",()=>{

link.style.opacity="1";

});


});





/* ANIMATION APPARITION DES ELEMENTS AU CHARGEMENT */


window.addEventListener("load",()=>{


document.querySelectorAll(".hero .reveal").forEach((element,index)=>{


setTimeout(()=>{


element.classList.add("active");


},300 + index*200);



});


});





/* OBSERVATION DES ELEMENTS DYNAMIQUES */


const dynamicObserver=new MutationObserver(()=>{


document.querySelectorAll(".reveal:not(.observed)").forEach(element=>{


element.classList.add("observed");


observer.observe(element);


});


});



dynamicObserver.observe(document.body,{

childList:true,

subtree:true

});






/* VERIFICATION FORMULAIRE */

const inputs=document.querySelectorAll("input,textarea");


inputs.forEach(input=>{


input.addEventListener("input",()=>{


if(input.value.trim()!==""){


input.style.borderColor="rgba(0,140,255,.8)";


}else{


input.style.borderColor="rgba(255,255,255,.15)";


}


});


});






/* PREVENTION ERREURS IMAGE */

document.querySelectorAll("img").forEach(img=>{


img.addEventListener("error",()=>{


img.style.display="none";


});


});



</script>






<!-- DONNEES STRUCTUREES SUPPLEMENTAIRES SEO -->

<script type="application/ld+json">

{
"@context":"https://schema.org",
"@type":"WebSite",
"name":"CVR PRECISION",
"url":"https://cvrprecision.fr",
"potentialAction":{
"@type":"SearchAction",
"target":"https://cvrprecision.fr/?s={search_term_string}",
"query-input":"required name=search_term_string"
}
}

</script>






<script type="application/ld+json">

{
"@context":"https://schema.org",
"@type":"Organization",
"name":"CVR PRECISION",
"url":"https://cvrprecision.fr",
"logo":"logo.png",
"contactPoint":{
"@type":"ContactPoint",
"telephone":"+33695527388",
"contactType":"customer service",
"email":"cvr.precision@gmail.com",
"areaServed":"FR",
"availableLanguage":"French"
}
}

</script>






<!-- FIN DU SITE -->

</main>





</body>

</html>
