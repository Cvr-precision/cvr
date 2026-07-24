
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
    
    <!-- Twitter -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CVR PRECISION">
    <meta name="twitter:description" content="Rachat de matériel industriel d'occasion premium.">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&amp;family=Space+Grotesk:wght@500;600;700&amp;display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">
    
    <style>
        :root {
            --black: #05080d;
            --dark: #0a0f1a;
            --dark2: #111827;
            --steel: #334155;
            --white: #ffffff;
            --gray: #94a3b8;
            --blue: #008cff;
            --blue2: #00c6ff;
            --accent: #0ea5e9;
            --glass: rgba(255,255,255,0.06);
            --border: rgba(255,255,255,0.1);
            --shadow: 0 25px 70px rgba(0,0,0,0.5);
            --radius: 24px;
            --transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        html {
            scroll-behavior: smooth;
        }
        
        body {
            font-family: 'Inter', system_ui, sans-serif;
            background: var(--black);
            color: var(--white);
            line-height: 1.7;
            overflow-x: hidden;
        }
        
        h1, h2, h3 {
            font-family: 'Space Grotesk', sans-serif;
            font-weight: 700;
            line-height: 1.1;
        }
        
        a {
            color: inherit;
            text-decoration: none;
            transition: var(--transition);
        }
        
        img {
            max-width: 100%;
            display: block;
        }
        
        section {
            position: relative;
            padding: 120px 5%;
        }
        
        .container {
            max-width: 1420px;
            margin: 0 auto;
        }
        
        /* PRELOADER */
        .loader {
            position: fixed;
            inset: 0;
            background: var(--black);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 9999;
            transition: opacity 0.8s ease;
        }
        
        .loader.hide {
            opacity: 0;
            pointer-events: none;
        }
        
        .loader span {
            width: 64px;
            height: 64px;
            border: 5px solid rgba(255,255,255,0.1);
            border-top-color: var(--blue);
            border-radius: 50%;
            animation: spin 1s linear infinite;
        }
        
        @keyframes spin {
            to { transform: rotate(360deg); }
        }
        
        /* HEADER */
        header {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000;
            padding: 28px 5%;
            transition: var(--transition);
        }
        
        header.scrolled {
            background: rgba(5, 8, 13, 0.92);
            backdrop-filter: blur(20px);
            padding: 18px 5%;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.4);
        }
        
        .navbar {
            display: flex;
            align-items: center;
            justify-content: space-between;
            max-width: 1420px;
            margin: 0 auto;
        }
        
        .logo img {
            height: 52px;
            width: auto;
            filter: drop-shadow(0 0 15px rgba(0, 140, 255, 0.3));
        }
        
        .nav-links {
            display: flex;
            gap: 42px;
            align-items: center;
            font-weight: 500;
            font-size: 15.5px;
        }
        
        .nav-links a {
            position: relative;
        }
        
        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: -6px;
            left: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(to right, var(--blue), var(--blue2));
            transition: width 0.3s ease;
        }
        
        .nav-links a:hover::after {
            width: 100%;
        }
        
        .menu-btn {
            display: none;
            font-size: 28px;
            cursor: pointer;
            color: white;
        }
        
        /* HERO */
        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            position: relative;
            padding-top: 100px;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            inset: 0;
            background: radial-gradient(circle at 30% 20%, rgba(0, 140, 255, 0.18), transparent 60%),
                        radial-gradient(circle at 80% 70%, rgba(0, 198, 255, 0.12), transparent 60%);
            z-index: 0;
        }
        
        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 820px;
        }
        
        .hero h1 {
            font-size: clamp(3rem, 7.5vw, 5.8rem);
            letter-spacing: -3.5px;
            line-height: 1.05;
            margin-bottom: 28px;
        }
        
        .hero h1 span {
            background: linear-gradient(90deg, var(--blue), var(--blue2));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .hero p {
            font-size: clamp(1.15rem, 2.2vw, 1.45rem);
            color: #cbd5e1;
            max-width: 620px;
            margin-bottom: 48px;
        }
        
        .hero-buttons {
            display: flex;
            gap: 22px;
            flex-wrap: wrap;
        }
        
        .btn {
            padding: 18px 38px;
            border-radius: 9999px;
            font-weight: 700;
            font-size: 1.05rem;
            display: inline-flex;
            align-items: center;
            gap: 12px;
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }
        
        .btn-primary {
            background: linear-gradient(90deg, var(--blue), var(--accent));
            box-shadow: 0 0 40px rgba(0, 140, 255, 0.5);
        }
        
        .btn-primary:hover {
            transform: translateY(-6px);
            box-shadow: 0 0 65px rgba(0, 140, 255, 0.7);
        }
        
        .btn-outline {
            border: 1.5px solid rgba(255,255,255,0.25);
            background: rgba(255,255,255,0.04);
            backdrop-filter: blur(12px);
        }
        
        .btn-outline:hover {
            background: white;
            color: #05080d;
            border-color: white;
        }
        
        .hero-image {
            position: absolute;
            right: 6%;
            bottom: 8%;
            width: 48%;
            z-index: 1;
            border-radius: 28px;
            overflow: hidden;
            box-shadow: var(--shadow);
        }
        
        .hero-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.8s ease;
        }
        
        .hero-image:hover img {
            transform: scale(1.04);
        }
        
        /* SECTION TITLE */
        .section-title {
            text-align: center;
            margin-bottom: 80px;
        }
        
        .section-title h2 {
            font-size: clamp(2.2rem, 4.5vw, 3.6rem);
            margin-bottom: 16px;
        }
        
        .section-title p {
            color: var(--gray);
            font-size: 1.15rem;
            max-width: 620px;
            margin: 0 auto;
        }
        
        /* REVEAL */
        .reveal {
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.9s cubic-bezier(0.25, 0.1, 0.25, 1);
        }
        
        .reveal.active {
            opacity: 1;
            transform: none;
        }
        
        /* PRESENTATION */
        .presentation-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 80px;
            align-items: center;
        }
        
        .presentation-text p {
            font-size: 1.15rem;
            color: #cbd5e1;
            margin-bottom: 26px;
        }
        
        .glass-card {
            background: var(--glass);
            border: 1px solid var(--border);
            padding: 42px 34px;
            border-radius: var(--radius);
            backdrop-filter: blur(22px);
            transition: var(--transition);
            box-shadow: var(--shadow);
        }
        
        .glass-card:hover {
            transform: translateY(-12px);
            border-color: var(--blue);
        }
        
        .glass-card i {
            font-size: 48px;
            color: var(--blue);
            margin-bottom: 24px;
            display: block;
        }
        
        /* EQUIPMENT GRID */
        .equipment-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 28px;
        }
        
        .equipment-card {
            background: linear-gradient(145deg, rgba(255,255,255,0.07), rgba(255,255,255,0.02));
            border: 1px solid var(--border);
            border-radius: var(--radius);
            padding: 42px 32px;
            text-align: center;
            transition: var(--transition);
            backdrop-filter: blur(16px);
        }
        
        .equipment-card:hover {
            transform: translateY(-16px);
            border-color: var(--blue);
            box-shadow: 0 30px 60px rgba(0, 140, 255, 0.2);
        }
        
        .equipment-card i {
            font-size: 46px;
            color: var(--blue);
            margin-bottom: 22px;
        }
        
        /* SERVICES & ADVANTAGES */
        .services-grid,
        .advantages-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
            gap: 30px;
        }
        
        .service-card,
        .advantage-card {
            background: var(--glass);
            border: 1px solid var(--border);
            padding: 42px 34px;
            border-radius: var(--radius);
            transition: var(--transition);
            backdrop-filter: blur(18px);
        }
        
        .service-card:hover,
        .advantage-card:hover {
            transform: translateY(-12px);
            border-color: var(--blue);
        }
        
        .advantage-card .number {
            position: absolute;
            font-size: 110px;
            font-weight: 900;
            color: rgba(255,255,255,0.04);
            right: 24px;
            top: 12px;
            line-height: 1;
        }
        
        /* STATS */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 28px;
        }
        
        .stat-card {
            text-align: center;
            padding: 48px 24px;
            background: var(--glass);
            border: 1px solid var(--border);
            border-radius: var(--radius);
            backdrop-filter: blur(16px);
        }
        
        .stat-card strong {
            font-size: 3.4rem;
            font-weight: 800;
            display: block;
            margin-bottom: 8px;
        }
        
        /* TIMELINE */
        .timeline {
            max-width: 820px;
            margin: 0 auto;
            position: relative;
        }
        
        .timeline::before {
            content: '';
            position: absolute;
            left: 38px;
            top: 0;
            bottom: 0;
            width: 3px;
            background: linear-gradient(to bottom, var(--blue), transparent);
        }
        
        .timeline-item {
            display: flex;
            gap: 42px;
            margin-bottom: 60px;
            position: relative;
        }
        
        .timeline-icon {
            width: 78px;
            height: 78px;
            background: var(--glass);
            border: 1px solid var(--border);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            z-index: 2;
        }
        
        .timeline-icon i {
            font-size: 32px;
            color: var(--blue);
        }
        
        /* CONTACT */
        .contact-grid {
            display: grid;
            grid-template-columns: 1fr 1.1fr;
            gap: 70px;
        }
        
        .contact-card {
            display: flex;
            gap: 26px;
            padding: 28px;
            background: rgba(255,255,255,0.05);
            border: 1px solid var(--border);
            border-radius: 20px;
            margin-bottom: 22px;
        }
        
        .contact-form {
            background: var(--glass);
            padding: 48px;
            border-radius: var(--radius);
            border: 1px solid var(--border);
            backdrop-filter: blur(20px);
        }
        
        .form-group {
            margin-bottom: 26px;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 8px;
            font-weight: 600;
            font-size: 0.95rem;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 18px 22px;
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.15);
            border-radius: 16px;
            color: white;
            font-size: 1rem;
        }
        
        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: var(--blue);
            box-shadow: 0 0 0 3px rgba(0, 140, 255, 0.2);
        }
        
        /* FOOTER */
        footer {
            background: #03050a;
            padding: 90px 5% 40px;
            border-top: 1px solid rgba(255,255,255,0.08);
        }
        
        .footer-grid {
            display: grid;
            grid-template-columns: 2fr 1fr 1fr;
            gap: 60px;
        }
        
        /* RESPONSIVE */
        @media (max-width: 1100px) {
            .presentation-grid {
                grid-template-columns: 1fr;
                gap: 60px;
            }
            
            .hero-image {
                position: relative;
                width: 100%;
                right: auto;
                bottom: auto;
                margin-top: 60px;
            }
        }
        
        @media (max-width: 768px) {
            .nav-links {
                position: fixed;
                top: 0;
                right: -100%;
                width: 300px;
                height: 100vh;
                background: #070b12;
                flex-direction: column;
                align-items: center;
                justify-content: center;
                gap: 36px;
                transition: 0.5s cubic-bezier(0.32, 0.72, 0, 1);
                box-shadow: -30px 0 60px rgba(0,0,0,0.6);
            }
            
            .nav-links.active {
                right: 0;
            }
            
            .menu-btn {
                display: block;
            }
            
            section {
                padding: 90px 6%;
            }
            
            .equipment-grid,
            .services-grid,
            .advantages-grid,
            .stats-grid {
                grid-template-columns: 1fr;
            }
            
            .hero-buttons {
                flex-direction: column;
                align-items: stretch;
            }
            
            .btn {
                justify-content: center;
            }
            
            .contact-grid {
                grid-template-columns: 1fr;
            }
            
            .footer-grid {
                grid-template-columns: 1fr;
            }
        }
        
        /* ADDITIONAL STYLES FOR PREMIUM FEEL */
        .metallic-text {
            background: linear-gradient(90deg, #e2e8f0, #cbd5e1, #e2e8f0);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .btn::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 40%;
            height: 200%;
            background: linear-gradient(120deg, transparent, rgba(255,255,255,0.4), transparent);
            transform: skewX(-25deg);
            transition: left 0.6s;
        }
        
        .btn:hover::after {
            left: 120%;
        }
    </style>
</head>
<body>
    <!-- PRELOADER -->
    <div class="loader">
        <span></span>
    </div>
    
    <!-- HEADER -->
    <header>
        <div class="navbar">
            <a href="#" class="logo">
                <img src="logo.png" alt="CVR PRECISION">
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
            <div class="container" style="position: relative; z-index: 2;">
                <div class="hero-content reveal">
                    <h1>Nous rachetons votre <span>matériel industriel</span> d'occasion</h1>
                    <p>Une solution premium, rapide et sécurisée pour valoriser vos machines-outils, centres d'usinage et équipements professionnels.</p>
                    
                    <div class="hero-buttons">
                        <a href="#contact" class="btn btn-primary">
                            <i class="fa-solid fa-camera"></i>
                            Demander une estimation gratuite
                        </a>
                        <a href="tel:+33695527388" class="btn btn-outline">
                            <i class="fa-solid fa-phone"></i>
                            Nous contacter
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="hero-image">
                <img src="https://images.unsplash.com/photo-1581094794329-c8112a89af12?auto=format&amp;fit=crop&amp;w=1600&amp;q=85" alt="Machine-outil industrielle moderne - CVR PRECISION">
            </div>
        </section>
        
        <!-- PRESENTATION -->
        <section id="presentation">
            <div class="container">
                <div class="section-title reveal">
                    <h2>CVR PRECISION</h2>
                    <p>Expertise industrielle au service de la valorisation de vos équipements</p>
                </div>
                
                <div class="presentation-grid">
                    <div class="presentation-text reveal">
                        <p>CVR PRECISION rachète du matériel professionnel et industriel d’occasion à l’unité ou en lots importants.</p>
                        <p>Vous possédez des machines inutilisées, en fin de vie ou en surplus ? Nous proposons une estimation rapide et sérieuse à partir de photos et données techniques.</p>
                        <p>Intervention complète : démontage, chargement, transport et paiement sécurisé sur tout le territoire français.</p>
                        
                        <a href="#contact" class="btn btn-primary" style="margin-top: 20px;">
                            <i class="fa-solid fa-paper-plane"></i>
                            Envoyer vos équipements
                        </a>
                    </div>
                    
                    <div class="presentation-card reveal">
                        <div class="glass-card">
                            <i class="fa-solid fa-industry"></i>
                            <h3>Spécialiste machines-outils</h3>
                            <p>Rachat et revalorisation de centres d’usinage, tours CNC, fraiseuses et équipements lourds.</p>
                        </div>
                        <div class="glass-card">
                            <i class="fa-solid fa-truck-fast"></i>
                            <h3>Logistique complète</h3>
                            <p>Organisation professionnelle du démontage, transport et sortie d’usine.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- RACHAT -->
        <section id="rachat" style="background: linear-gradient(180deg, #05080d, #0a0f1a);">
            <div class="container">
                <div class="section-title reveal">
                    <h2>Nous rachetons</h2>
                    <p>Une gamme étendue de matériels industriels professionnels</p>
                </div>
                
                <div class="equipment-grid">
                    <div class="equipment-card reveal">
                        <i class="fa-solid fa-gears"></i>
                        <h3>Machines-outils</h3>
                        <p>Centres d’usinage, tours CNC, fraiseuses, aléseuses.</p>
                    </div>
                    <div class="equipment-card reveal">
                        <i class="fa-solid fa-bolt"></i>
                        <h3>Groupes électrogènes</h3>
                        <p>Générateurs industriels et systèmes de secours.</p>
                    </div>
                    <div class="equipment-card reveal">
                        <i class="fa-solid fa-tree"></i>
                        <h3>Machines à bois</h3>
                        <p>Équipements professionnels pour le travail du bois.</p>
                    </div>
                    <div class="equipment-card reveal">
                        <i class="fa-solid fa-industry"></i>
                        <h3>Production aluminium</h3>
                        <p>Machines de profilage et découpe aluminium.</p>
                    </div>
                    <div class="equipment-card reveal">
                        <i class="fa-solid fa-dolly"></i>
                        <h3>Manutention</h3>
                        <p>Chariots élévateurs, ponts roulants, équipements logistiques.</p>
                    </div>
                    <div class="equipment-card reveal">
                        <i class="fa-solid fa-truck-monster"></i>
                        <h3>Matériel TP</h3>
                        <p>Engins de chantier et véhicules industriels.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- SERVICES -->
        <section id="services">
            <div class="container">
                <div class="section-title reveal">
                    <h2>Nos prestations</h2>
                    <p>Une prise en charge complète et professionnelle</p>
                </div>
                
                <div class="services-grid">
                    <div class="service-card reveal">
                        <i class="fa-solid fa-camera"></i>
                        <h3>Estimation sur photos</h3>
                        <p>Analyse rapide et experte à partir des visuels et informations fournies.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-chart-line"></i>
                        <h3>Valorisation optimale</h3>
                        <p>Revente ou réutilisation dans le respect des standards du marché.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-screwdriver-wrench"></i>
                        <h3>Achat en l’état</h3>
                        <p>Nous acceptons les machines avec ou sans défauts techniques.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-map-location-dot"></i>
                        <h3>Intervention France entière</h3>
                        <p>Logistique nationale depuis votre site industriel.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-truck"></i>
                        <h3>Transport sécurisé</h3>
                        <p>Chargement, manutention et documents CMR complets.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-money-bill-transfer"></i>
                        <h3>Paiement rapide</h3>
                        <p>Règlement avant enlèvement selon modalités convenues.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- AVANTAGES -->
        <section id="avantages" style="background: #05080d;">
            <div class="container">
                <div class="section-title reveal">
                    <h2>Pourquoi choisir CVR PRECISION</h2>
                    <p>Un partenaire fiable et réactif</p>
                </div>
                
                <div class="advantages-grid">
                    <div class="advantage-card reveal">
                        <div class="number">01</div>
                        <i class="fa-solid fa-bolt"></i>
                        <h3>Réactivité</h3>
                        <p>Réponse sous 48h maximum.</p>
                    </div>
                    <div class="advantage-card reveal">
                        <div class="number">02</div>
                        <i class="fa-solid fa-user-tie"></i>
                        <h3>Expertise</h3>
                        <p>Connaissance approfondie du secteur industriel.</p>
                    </div>
                    <div class="advantage-card reveal">
                        <div class="number">03</div>
                        <i class="fa-solid fa-shield-halved"></i>
                        <h3>Sécurité</h3>
                        <p>Transactions claires et paiement sécurisé.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- CHIFFRES -->
        <section id="chiffres">
            <div class="container">
                <div class="stats-grid">
                    <div class="stat-card reveal">
                        <i class="fa-solid fa-industry"></i>
                        <strong class="counter" data-target="620">0</strong>
                        <span>Matériels valorisés</span>
                    </div>
                    <div class="stat-card reveal">
                        <i class="fa-solid fa-location-dot"></i>
                        <strong class="counter" data-target="120">0</strong>
                        <span>Déplacements réalisés</span>
                    </div>
                    <div class="stat-card reveal">
                        <i class="fa-solid fa-users"></i>
                        <strong class="counter" data-target="18">0</strong>
                        <span>Années d’expérience</span>
                    </div>
                    <div class="stat-card reveal">
                        <i class="fa-solid fa-truck-fast"></i>
                        <strong class="counter" data-target="24">0</strong>
                        <span>Heures de réponse moyenne</span>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- METHODE -->
        <section id="methode">
            <div class="container">
                <div class="section-title reveal">
                    <h2>Notre méthode</h2>
                    <p>Simple, transparente et efficace</p>
                </div>
                
                <div class="timeline">
                    <div class="timeline-item reveal">
                        <div class="timeline-icon">
                            <i class="fa-solid fa-camera"></i>
                        </div>
                        <div class="timeline-content">
                            <h3>1. Envoi des informations</h3>
                            <p>Photos, références, années de fabrication et caractéristiques.</p>
                        </div>
                    </div>
                    <div class="timeline-item reveal">
                        <div class="timeline-icon">
                            <i class="fa-solid fa-magnifying-glass-chart"></i>
                        </div>
                        <div class="timeline-content">
                            <h3>2. Analyse &amp; estimation</h3>
                            <p>Proposition chiffrée rapide par notre équipe technique.</p>
                        </div>
                    </div>
                    <div class="timeline-item reveal">
                        <div class="timeline-icon">
                            <i class="fa-solid fa-file-signature"></i>
                        </div>
                        <div class="timeline-content">
                            <h3>3. Accord &amp; planification</h3>
                            <p>Validation des modalités d’enlèvement.</p>
                        </div>
                    </div>
                    <div class="timeline-item reveal">
                        <div class="timeline-icon">
                            <i class="fa-solid fa-truck-ramp-box"></i>
                        </div>
                        <div class="timeline-content">
                            <h3>4. Enlèvement</h3>
                            <p>Démontage, chargement et transport professionnel.</p>
                        </div>
                    </div>
                    <div class="timeline-item reveal">
                        <div class="timeline-icon">
                            <i class="fa-solid fa-euro-sign"></i>
                        </div>
                        <div class="timeline-content">
                            <h3>5. Paiement</h3>
                            <p>Règlement intégral avant enlèvement.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- CONTACT -->
        <section id="contact">
            <div class="container">
                <div class="section-title reveal">
                    <h2>Contactez-nous</h2>
                    <p>Une question ? Un projet de rachat ?</p>
                </div>
                
                <div class="contact-grid">
                    <div class="contact-info reveal">
                        <div class="contact-card">
                            <i class="fa-solid fa-building"></i>
                            <div>
                                <h3>CVR PRECISION</h3>
                                <p>Spécialiste rachat industriel</p>
                            </div>
                        </div>
                        <div class="contact-card">
                            <i class="fa-solid fa-user"></i>
                            <div>
                                <h3>Eric</h3>
                                <p>Votre interlocuteur dédié</p>
                            </div>
                        </div>
                        <div class="contact-card">
                            <i class="fa-solid fa-phone"></i>
                            <div>
                                <h3>Téléphone</h3>
                                <p><a href="tel:+33695527388">+33 6 95 52 73 88</a></p>
                            </div>
                        </div>
                        <div class="contact-card">
                            <i class="fa-solid fa-envelope"></i>
                            <div>
                                <h3>Email</h3>
                                <p><a href="mailto:cvr.precision@gmail.com">cvr.precision@gmail.com</a></p>
                            </div>
                        </div>
                        <div class="contact-card">
                            <i class="fa-solid fa-location-dot"></i>
                            <div>
                                <h3>Adresse</h3>
                                <p>131 Boulevard Carnot<br>78110 Le Vésinet, France</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="contact-form reveal">
                        <form action="https://formspree.io/f/xaqrpknp" method="POST">
                            <input type="hidden" name="_subject" value="Nouvelle demande CVR PRECISION">
                            <input type="hidden" name="_next" value="https://cvrprecision.fr/#contact">
                            
                            <div class="form-group">
                                <label for="nom">Nom complet *</label>
                                <input type="text" id="nom" name="nom" required>
                            </div>
                            <div class="form-group">
                                <label for="entreprise">Entreprise</label>
                                <input type="text" id="entreprise" name="entreprise">
                            </div>
                            <div class="form-group">
                                <label for="telephone">Téléphone *</label>
                                <input type="tel" id="telephone" name="telephone" required>
                            </div>
                            <div class="form-group">
                                <label for="email">Email *</label>
                                <input type="email" id="email" name="email" required>
                            </div>
                            <div class="form-group">
                                <label for="description">Description du matériel</label>
                                <textarea id="description" name="description" rows="3" placeholder="Marque, modèle, année..."></textarea>
                            </div>
                            <div class="form-group">
                                <label for="message">Message additionnel</label>
                                <textarea id="message" name="message" rows="4"></textarea>
                            </div>
                            
                            <button type="submit" class="btn btn-primary" style="width: 100%; justify-content: center;">
                                <i class="fa-solid fa-paper-plane"></i>
                                Envoyer la demande d'estimation
                            </button>
                        </form>
                    </div>
                </div>
                
                <div class="map-container" style="margin-top: 80px; border-radius: 24px; overflow: hidden; border: 1px solid var(--border);">
                    <iframe src="https://maps.google.com/maps?q=131%20Boulevard%20Carnot%2078110%20Le%20V%C3%A9sinet&amp;t=&amp;z=15&amp;ie=UTF8&amp;iwloc=&amp;output=embed" width="100%" height="420" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </div>
        </section>
        
        <!-- ENGAGEMENT -->
        <section id="engagement" style="background: #05080d;">
            <div class="container">
                <div class="section-title reveal">
                    <h2>Notre engagement</h2>
                    <p>Transparence et responsabilité industrielle</p>
                </div>
                
                <div class="services-grid">
                    <div class="service-card reveal">
                        <i class="fa-solid fa-recycle"></i>
                        <h3>Économie circulaire</h3>
                        <p>Donner une seconde vie aux équipements pour réduire l’empreinte industrielle.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-handshake-angle"></i>
                        <h3>Relation de confiance</h3>
                        <p>Accompagnement personnalisé tout au long du processus.</p>
                    </div>
                    <div class="service-card reveal">
                        <i class="fa-solid fa-industry"></i>
                        <h3>Connaissance métier</h3>
                        <p>Équipe experte du secteur des machines-outils.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- CTA -->
        <section id="cta">
            <div class="container">
                <div class="cta-box reveal" style="background: linear-gradient(135deg, rgba(0,140,255,0.22), rgba(0,198,255,0.08)); padding: 92px 60px; border-radius: 32px; text-align: center; position: relative; overflow: hidden;">
                    <h2 style="font-size: clamp(2.4rem, 5vw, 3.8rem); margin-bottom: 24px;">Prêt à valoriser votre matériel ?</h2>
                    <p style="font-size: 1.3rem; max-width: 680px; margin: 0 auto 42px;">Obtenez une estimation gratuite en quelques clics.</p>
                    <a href="#contact" class="btn btn-primary" style="font-size: 1.2rem; padding: 22px 52px;">
                        <i class="fa-solid fa-arrow-right"></i>
                        Démarrer maintenant
                    </a>
                </div>
            </div>
        </section>
    </main>
    
    <!-- FOOTER -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div>
                    <img src="logo.png" alt="CVR PRECISION" style="height: 68px; margin-bottom: 22px;">
                    <p style="color: var(--gray); max-width: 360px;">Rachat et valorisation professionnelle de matériels industriels d’occasion partout en France.</p>
                </div>
                
                <div>
                    <h3 style="margin-bottom: 22px; font-size: 1.1rem;">Navigation</h3>
                    <a href="#accueil" style="display: block; margin-bottom: 12px; color: #cbd5e1;">Accueil</a>
                    <a href="#presentation" style="display: block; margin-bottom: 12px; color: #cbd5e1;">Présentation</a>
                    <a href="#rachat" style="display: block; margin-bottom: 12px; color: #cbd5e1;">Matériels</a>
                    <a href="#contact" style="display: block; color: #cbd5e1;">Contact</a>
                </div>
                
                <div>
                    <h3 style="margin-bottom: 22px; font-size: 1.1rem;">Contact</h3>
                    <p style="color: var(--gray); margin-bottom: 10px;"><i class="fa-solid fa-phone"></i> +33 6 95 52 73 88</p>
                    <p style="color: var(--gray);"><i class="fa-solid fa-envelope"></i> cvr.precision@gmail.com</p>
                </div>
            </div>
            
            <div style="margin-top: 80px; padding-top: 30px; border-top: 1px solid rgba(255,255,255,0.1); text-align: center; color: #64748b; font-size: 0.95rem;">
                © 2026 CVR PRECISION - Tous droits réservés.
            </div>
        </div>
    </footer>
    
    <!-- BACK TO TOP -->
    <button id="top-btn" style="position: fixed; bottom: 40px; right: 40px; width: 58px; height: 58px; background: linear-gradient(135deg, var(--blue), var(--blue2)); border: none; border-radius: 50%; color: white; font-size: 22px; cursor: pointer; box-shadow: 0 10px 30px rgba(0,140,255,0.4); display: none; align-items: center; justify-content: center; z-index: 999;">
        <i class="fa-solid fa-arrow-up"></i>
    </button>
    
    <script>
        // PRELOADER
        window.addEventListener('load', () => {
            const loader = document.querySelector('.loader');
            setTimeout(() => {
                loader.classList.add('hide');
            }, 650);
        });
        
        // HEADER SCROLL
        const header = document.querySelector('header');
        window.addEventListener('scroll', () => {
            if (window.scrollY > 120) {
                header.classList.add('scrolled');
            } else {
                header.classList.remove('scrolled');
            }
        });
        
        // MOBILE MENU
        const menuBtn = document.getElementById('menu-btn');
        const navLinks = document.getElementById('nav-links');
        
        menuBtn.addEventListener('click', () => {
            navLinks.classList.toggle('active');
            const icon = menuBtn.querySelector('i');
            if (navLinks.classList.contains('active')) {
                icon.classList.remove('fa-bars');
                icon.classList.add('fa-xmark');
            } else {
                icon.classList.add('fa-bars');
                icon.classList.remove('fa-xmark');
            }
        });
        
        // Close menu on link click
        document.querySelectorAll('.nav-links a').forEach(link => {
            link.addEventListener('click', () => {
                navLinks.classList.remove('active');
                const icon = menuBtn.querySelector('i');
                icon.classList.add('fa-bars');
                icon.classList.remove('fa-xmark');
            });
        });
        
        // REVEAL ANIMATIONS
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('active');
                }
            });
        }, {
            threshold: 0.15,
            rootMargin: "0px 0px -60px 0px"
        });
        
        document.querySelectorAll('.reveal').forEach(el => {
            observer.observe(el);
        });
        
        // COUNTERS
        const counters = document.querySelectorAll('.counter');
        let started = false;
        
        const counterObserver = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting && !started) {
                    started = true;
                    counters.forEach(counter => {
                        const target = parseInt(counter.getAttribute('data-target'));
                        let count = 0;
                        const increment = Math.ceil(target / 45);
                        
                        const timer = setInterval(() => {
                            count += increment;
                            if (count >= target) {
                                counter.textContent = target;
                                clearInterval(timer);
                            } else {
                                counter.textContent = count;
                            }
                        }, 32);
                    });
                }
            });
        }, { threshold: 0.6 });
        
        const statsSection = document.getElementById('chiffres');
        if (statsSection) counterObserver.observe(statsSection);
        
        // BACK TO TOP
        const topBtn = document.getElementById('top-btn');
        
        window.addEventListener('scroll', () => {
            if (window.scrollY > 620) {
                topBtn.style.display = 'flex';
            } else {
                topBtn.style.display = 'none';
            }
        });
        
        topBtn.addEventListener('click', () => {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });
        
        // FORM SUCCESS HANDLING
        const form = document.querySelector('form');
        if (form) {
            form.addEventListener('submit', function() {
                setTimeout(() => {
                    const btn = form.querySelector('button');
                    const originalText = btn.innerHTML;
                    btn.innerHTML = `<i class="fa-solid fa-check"></i> Demande envoyée`;
                    btn.style.background = '#16a34a';
                    
                    setTimeout(() => {
                        form.reset();
                        btn.innerHTML = originalText;
                        btn.style.background = '';
                    }, 3800);
                }, 800);
            });
        }
        
        // SMOOTH ANCHOR LINKS
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);
                if (targetElement) {
                    e.preventDefault();
                    targetElement.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });
        
        // Keyboard ESC for mobile menu
        document.addEventListener('keydown', (e) => {
            if (e.key === "Escape" && navLinks.classList.contains('active')) {
                navLinks.classList.remove('active');
                const icon = menuBtn.querySelector('i');
                icon.classList.add('fa-bars');
                icon.classList.remove('fa-xmark');
            }
        });
        
        // Prevent horizontal scroll
        document.documentElement.style.overflowX = 'hidden';
    </script>
    
    <!-- SCHEMA.ORG -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "LocalBusiness",
        "name": "CVR PRECISION",
        "description": "Rachat de matériel industriel d'occasion, machines-outils et équipements professionnels.",
        "url": "https://cvrprecision.fr",
        "telephone": "+33695527388",
        "email": "cvr.precision@gmail.com",
        "address": {
            "@type": "PostalAddress",
            "streetAddress": "131 Boulevard Carnot",
            "addressLocality": "Le Vésinet",
            "postalCode": "78110",
            "addressCountry": "FR"
        },
        "areaServed": "France",
        "priceRange": "€€",
        "image": "logo.png"
    }
    </script>
</body>
</html>
