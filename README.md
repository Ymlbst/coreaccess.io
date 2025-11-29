<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>CoreAccess.io | Intelligence Artificielle & Quantique</title>
    <style>
        /* --- RESET & BASE --- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Police style Apple (San Francisco / System UI) */
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f5f5f7; /* Gris très clair Apple */
            color: #1d1d1f; /* Noir doux Apple */
            line-height: 1.6;
            -webkit-font-smoothing: antialiased; /* Lissage des polices */
        }

        /* Scroll fluide */
        html {
            scroll-behavior: smooth;
        }

        /* --- NAVIGATION (STYLE APPLE) --- */
        nav {
            position: sticky;
            top: 0;
            width: 100%;
            height: 48px; /* Hauteur standard Apple */
            background-color: rgba(255, 255, 255, 0.8); /* Semi-transparent */
            backdrop-filter: saturate(180%) blur(20px); /* Effet verre dépoli */
            border-bottom: 1px solid rgba(0,0,0,0.1);
            z-index: 1000;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .nav-content {
            width: 100%;
            max-width: 980px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        .logo {
            font-weight: 600;
            font-size: 1.1em;
            color: #1d1d1f;
            text-decoration: none;
            letter-spacing: -0.5px;
        }

        .nav-links {
            display: flex;
            gap: 30px;
        }

        .nav-links a {
            text-decoration: none;
            color: #1d1d1f;
            font-size: 0.85em;
            opacity: 0.8;
            transition: opacity 0.3s ease, color 0.3s ease;
        }

        .nav-links a:hover {
            opacity: 1;
            color: #0071e3; /* Bleu Apple */
        }

        /* --- HEADER / HERO SECTION --- */
        header {
            text-align: center;
            padding: 100px 20px 60px;
            max-width: 800px;
            margin: auto;
            animation: fadeIn 1s ease-out;
        }

        h1 {
            font-size: 3.5rem; /* Grand titre */
            font-weight: 700;
            letter-spacing: -1px;
            margin-bottom: 15px;
            color: #1d1d1f;
        }

        header p {
            font-size: 1.5rem;
            color: #86868b; /* Gris moyen */
            font-weight: 400;
            margin-bottom: 30px;
        }

        .cta-button {
            display: inline-block;
            background-color: #0071e3;
            color: white;
            padding: 12px 25px;
            border-radius: 980px; /* Pilule */
            text-decoration: none;
            font-size: 1em;
            transition: transform 0.2s ease, background-color 0.2s ease;
        }

        .cta-button:hover {
            background-color: #0077ed;
            transform: scale(1.02);
        }

        /* --- SECTIONS --- */
        section {
            padding: 80px 20px;
            max-width: 980px;
            margin: auto;
        }

        .section-title {
            font-size: 2.5rem;
            font-weight: 600;
            margin-bottom: 40px;
            text-align: center;
        }

        /* Grille pour les cartes */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        /* Cards (Cartes) interactives */
        .card {
            background: white;
            padding: 30px;
            border-radius: 18px; /* Coins arrondis Apple */
            box-shadow: 0 4px 20px rgba(0,0,0,0.04);
            transition: transform 0.3s cubic-bezier(0.25, 0.8, 0.25, 1), box-shadow 0.3s ease;
            cursor: pointer;
            text-align: center;
        }

        .card:hover {
            transform: translateY(-5px); /* Monte légèrement */
            box-shadow: 0 12px 30px rgba(0,0,0,0.08);
        }

        .card h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
        }

        .card p {
            color: #86868b;
        }

        /* --- FOOTER --- */
        footer {
            text-align: center;
            padding: 40px;
            background-color: #f5f5f7;
            color: #86868b;
            font-size: 0.8em;
            border-top: 1px solid #e5e5e5;
        }

        /* --- ANIMATION --- */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Responsive Mobile */
        @media (max-width: 600px) {
            h1 { font-size: 2.5rem; }
            header p { font-size: 1.2rem; }
            .nav-links { display: none; } /* Pour simplifier sur mobile */
        }
    </style>
</head>
<body>

    <nav>
        <div class="nav-content">
            <a href="#" class="logo">coreaccess.io</a>
            <div class="nav-links">
                <a href="#about">À propos</a>
                <a href="#data">Données</a>
                <a href="#quantum">Quantique</a>
                <a href="#contact">Contact</a>
            </div>
        </div>
    </nav>

    <header id="about">
        <h1>L'avenir des modèles IA.</h1>
        <p>Une base de données unifiée pour l'analyse environnementale et les technologies quantiques.</p>
        <a href="#data" class="cta-button">Découvrir le projet</a>
    </header>

    <section id="data">
        <h2 class="section-title">Domaines d'expertise</h2>
        <div class="grid">
            <div class="card">
                <h3>Big Data Climatique</h3>
                <p>Accumulation massive de données environnementales pour prédire les cycles futurs.</p>
            </div>
            <div class="card">
                <h3 id="quantum">Modèles Quantiques</h3>
                <p>Recherche de motifs complexes grâce à la puissance de calcul non-binaire.</p>
            </div>
            <div class="card">
                <h3>Énergies Alternatives</h3>
                <p>Optimisation des secteurs industriels via l'analyse prédictive.</p>
            </div>
        </div>
    </section>

    <section id="contact" style="background: white; border-radius: 20px; margin-bottom: 40px; text-align: center;">
        <h2 class="section-title">Rejoindre l'aventure</h2>
        <p style="color: #86868b; max-width: 600px; margin: auto; margin-bottom: 20px;">
            CoreAccess monte en maturité. Suivez l'évolution du projet pluriel.
        </p>
        <a href="mailto:contact@coreaccess.io" class="cta-button" style="background-color: #1d1d1f;">Me contacter</a>
    </section>

    <footer>
        <p>Copyright © 2025 Saint Yanis. Tous droits réservés.</p>
        <p>CoreAccess.io - Projet Étudiant Maths/Info</p>
    </footer>

    <script>
        // Petit script pour rendre le scroll encore plus fluide sur les ancres
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
