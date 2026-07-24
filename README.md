<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CVR PRECISION | Rachat de Matériel Industriel d'Occasion</title>
    <meta name="description" content="CVR PRECISION rachète vos machines-outils, centres d'usinage, équipements industriels et matériels professionnels d'occasion. Estimation rapide sur photos. Intervention nationale.">
    <meta name="keywords" content="rachat machine outil, machines industrielles occasion, centre usinage occasion, matériel industriel occasion, rachat équipement industriel, valorisation machines CNC">
    <meta name="author" content="CVR PRECISION">
    <meta name="robots" content="index, follow">
    <meta name="theme-color" content="#08111f">
    <link rel="canonical" href="https://cvrprecision.fr/">
    
    <!-- Open Graph -->
    <meta property="og:title" content="CVR PRECISION - Rachat de Matériel Industriel d'Occasion">
    <meta property="og:description" content="Rachat rapide et sécurisé de vos équipements industriels. Estimation sur photos. Intervention partout en France.">
    <meta property="og:type" content="website">
    <meta property="og:image" content="logo.png">
    <meta property="og:url" content="https://cvrprecision.fr/">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Space+Grotesk:wght@500;600;700&amp;display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    
    <style>
        :root {
            --black: #05080d;
            --dark: #0a0f1a;
            --blue: #008cff;
            --blue2: #00c6ff;
            --accent: #0ea5e9;
            --glass: rgba(255,255,255,0.06);
            --border: rgba(255,255,255,0.1);
            --radius: 24px;
            --shadow: 0 25px 70px rgba(0,0,0,0.5);
        }
        
        * { margin:0; padding:0; box-sizing:border-box; }
        html { scroll-behavior:smooth; }
        
        body {
            font-family:'Inter',sans-serif;
            background:var(--black);
            color:white;
            line-height:1.7;
            overflow-x:hidden;
        }
        
        h1,h2,h3 { font-family:'Space Grotesk',sans-serif; font-weight:700; }
        
        img { max-width:100%; height:auto; display:block; }
        
        .container { max-width:1420px; margin:0 auto; padding:0 5%; }
        
        /* HEADER */
        header {
            position:fixed;
            top:0; left:0; right:0;
            z-index:1000;
            padding:28px 5%;
            transition:all .4s ease;
        }
        header.scrolled {
            background:rgba(5,8,13,0.95);
            backdrop-filter:blur(20px);
            padding:18px 5%;
        }
        
        .navbar { display:flex; align-items:center; justify-content:space-between; }
        .logo img { height:54px; width:auto; }
        .nav-links { display:flex; gap:42px; font-weight:500; }
        .menu-btn { display:none; font-size:28px; cursor:pointer; }
        
        /* HERO */
        .hero {
            min-height:100vh;
            display:flex;
            align-items:center;
            padding-top:100px;
            position:relative;
            overflow:hidden;
        }
        .hero h1 { font-size:clamp(3rem,7.5vw,5.8rem); line-height:1.05; letter-spacing:-3px; }
        .hero h1 span {
            background:linear-gradient(90deg,var(--blue),var(--blue2));
            -webkit-background-clip:text;
            -webkit-text-fill-color:transparent;
        }
        
        .hero-buttons { display:flex; gap:22px; flex-wrap:wrap; }
        
        .btn {
            padding:18px 38px;
            border-radius:9999px;
            font-weight:700;
            display:inline-flex;
            align-items:center;
            gap:12px;
        }
        .btn-primary { background:linear-gradient(90deg,var(--blue),var(--accent)); }
        
        /* CARDS & GRIDS */
        .grid { display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr)); gap:28px; }
        .card {
            background:var(--glass);
            border:1px solid var(--border);
            padding:35px;
            border-radius:var(--radius);
            backdrop-filter:blur(16px);
        }
        
        /* CONTACT FORM */
        .contact-form {
            background:var(--glass);
            padding:48px;
            border-radius:var(--radius);
            border:1px solid var(--border);
        }
        .form-group { margin-bottom:26px; }
        .form-group input,
        .form-group textarea {
            width:100%;
            padding:18px 22px;
            background:rgba(255,255,255,0.08);
            border:1px solid rgba(255,255,255,0.15);
            border-radius:16px;
            color:white;
        }
        
        /* RESPONSIVE */
        @media (max-width:768px) {
            .logo img { height:42px; }
            .nav-links {
                position:fixed;
                top:0; right:-100%;
                width:300px; height:100vh;
                background:#070b12;
                flex-direction:column;
                justify-content:center;
                gap:40px;
                transition:0.5s;
            }
            .nav-links.active { right:0; }
            .menu-btn { display:block; }
            .hero-buttons { flex-direction:column; }
            section { padding:90px 6%; }
        }
    </style>
</head>
<body>

    <div class="loader" style="position:fixed;inset:0;background:#05080d;display:flex;align-items:center;justify-content:center;z-index:9999;">
        <span style="width:64px;height:64px;border:5px solid rgba(255,255,255,0.1);border-top-color:#008cff;border-radius:50%;animation:spin 1s linear infinite;"></span>
    </div>

    <header>
        <div class="container navbar">
            <a href="#" class="logo">
                <img src="logo.png" alt="CVR PRECISION" onerror="this.src='https://via.placeholder.com/210x54/0a0f1a/008cff?text=CVR+PRECISION';this.onerror=null;">
            </a>
            
            <nav class="nav-links" id="nav-links">
                <a href="#accueil">Accueil</a>
                <a href="#presentation">Présentation</a>
                <a href="#rachat">Nous rachetons</a>
                <a href="#services">Prestations</a>
                <a href="#contact">Contact</a>
            </nav>
            
            <div class="menu-btn" id="menu-btn">
                <i class="fa-solid fa-bars"></i>
            </div>
        </div>
    </header>

    <main>
        <!-- HERO -->
        <section class="hero" id="accueil">
            <div class="container">
                <div class="hero-content">
                    <h1>Nous rachetons votre <span>matériel industriel</span> d'occasion</h1>
                    <p>Une solution premium, rapide et sécurisée pour valoriser vos équipements.</p>
                    <div class="hero-buttons">
                        <a href="#contact" class="btn btn-primary">Demander une estimation</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- PRESENTATION -->
        <section id="presentation">
            <div class="container">
                <div class="section-title">
                    <h2>CVR PRECISION</h2>
                    <p>Expertise industrielle au service de la valorisation de vos équipements</p>
                </div>
                <div class="grid">
                    <div class="card">
                        <p>Nous rachetons du matériel professionnel et industriel d’occasion.</p>
                    </div>
                    <div class="card">
                        <p>Estimation rapide sur photos et organisation complète du transport.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- RACHAT -->
        <section id="rachat">
            <div class="container">
                <div class="section-title">
                    <h2>Nous rachetons</h2>
                </div>
                <div class="grid">
                    <div class="card"><strong>Machines-outils</strong><br>Centres d'usinage, tours CNC</div>
                    <div class="card"><strong>Groupes électrogènes</strong></div>
                    <div class="card"><strong>Matériel de manutention</strong></div>
                    <div class="card"><strong>Engins de chantier</strong></div>
                </div>
            </div>
        </section>

        <!-- SERVICES -->
        <section id="services">
            <div class="container">
                <div class="section-title">
                    <h2>Nos prestations</h2>
                </div>
                <div class="grid">
                    <div class="card">Estimation sur photos</div>
                    <div class="card">Achat en l'état</div>
                    <div class="card">Transport national</div>
                    <div class="card">Paiement sécurisé</div>
                </div>
            </div>
        </section>

        <!-- CONTACT -->
        <section id="contact">
            <div class="container">
                <div class="section-title">
                    <h2>Contactez CVR PRECISION</h2>
                </div>
                <div class="contact-form" style="max-width:720px;margin:0 auto;">
                    <form action="https://formspree.io/f/xaqrpknp" method="POST">
                        <input type="hidden" name="_subject" value="Nouvelle demande CVR PRECISION">
                        <div class="form-group">
                            <label>Nom complet *</label>
                            <input type="text" name="nom" required>
                        </div>
                        <div class="form-group">
                            <label>Entreprise</label>
                            <input type="text" name="entreprise">
                        </div>
                        <div class="form-group">
                            <label>Téléphone *</label>
                            <input type="tel" name="telephone" required>
                        </div>
                        <div class="form-group">
                            <label>Email *</label>
                            <input type="email" name="email" required>
                        </div>
                        <div class="form-group">
                            <label>Description du matériel</label>
                            <textarea name="description" rows="4"></textarea>
                        </div>
                        <button type="submit" class="btn btn-primary" style="width:100%;padding:20px;">Envoyer la demande</button>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container" style="text-align:center;padding:60px 5%;">
            <p>© 2026 CVR PRECISION - Tous droits réservés.</p>
        </div>
    </footer>

    <script>
        // Preloader
        window.addEventListener('load', () => {
            document.querySelector('.loader').style.opacity = '0';
            setTimeout(() => document.querySelector('.loader').remove(), 800);
        });

        // Mobile Menu
        const menuBtn = document.getElementById('menu-btn');
        const navLinks = document.getElementById('nav-links');
        
        menuBtn.addEventListener('click', () => {
            navLinks.classList.toggle('active');
            const icon = menuBtn.querySelector('i');
            icon.classList.toggle('fa-bars');
            icon.classList.toggle('fa-xmark');
        });

        // Form success
        document.querySelector('form').addEventListener('submit', function() {
            setTimeout(() => alert("✅ Demande envoyée avec succès !"), 800);
        });
    </script>
</body>
</html>
