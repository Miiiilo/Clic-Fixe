# Clic-Fixe
Services de réparation et rénovation domestique - Réparations en un clic!
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clic & Fixe Bricolage - Réparations domestiques en un clic</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50 0%, #4a6580 100%);
            color: white;
            padding: 30px 0;
            text-align: center;
            border-radius: 0 0 20px 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
        }
        
        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .logo-circle {
            width: 120px;
            height: 120px;
            background: #ff9900;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 40px;
            font-weight: bold;
            color: white;
            box-shadow: 0 0 20px rgba(255, 153, 0, 0.5);
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.4rem;
            margin-bottom: 20px;
            color: #ffcc80;
        }
        
        .bio-section {
            background: white;
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
        }
        
        h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #ff9900;
        }
        
        .bio-text {
            font-size: 1.1rem;
            margin-bottom: 15px;
            line-height: 1.8;
        }
        
        .services {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .service-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
        }
        
        .service-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: #2c3e50;
        }
        
        .why-choose {
            background: #e9f7ef;
            border-radius: 15px;
            padding: 30px;
            margin: 30px 0;
        }
        
        .benefits-list {
            list-style: none;
        }
        
        .benefits-list li {
            margin-bottom: 10px;
            padding-left: 30px;
            position: relative;
        }
        
        .benefits-list li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #28a745;
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        .contact-info {
            text-align: center;
            margin-top: 30px;
            padding: 20px;
            background: #2c3e50;
            color: white;
            border-radius: 15px;
        }
        
        .btn {
            display: inline-block;
            background: #ff9900;
            color: white;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
            transition: background 0.3s ease;
        }
        
        .btn:hover {
            background: #e68a00;
        }
        
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px;
            color: #777;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.2rem;
            }
            
            .tagline {
                font-size: 1.2rem;
            }
            
            .services {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo">
                <div class="logo-circle">C&F</div>
            </div>
            <h1>Clic & Fixe Bricolage</h1>
            <p class="tagline">Réparations domestiques en un clic!</p>
        </div>
    </header>

    <div class="container">
        <section class="bio-section">
            <h2>Bienvenue chez Clic & Fixe Bricolage</h2>
            <p class="bio-text">
                <strong>Clic & Fixe Bricolage</strong> - la solution optimale pour tous vos besoins de réparation et de rénovation domestique!
            </p>
            
            <h3>Nous proposons des services complets et professionnels dans:</h3>
            <div class="services">
                <div class="service-card">
                    <div class="service-icon">🚰</div>
                    <h3>Plomberie</h3>
                    <p>Réparations de plomberie et fuites d'eau</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">💡</div>
                    <h3>Électricité</h3>
                    <p>Travaux électriques et installation d'ampoules</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🔨</div>
                    <h3>Menuiserie</h3>
                    <p>Travaux de menuiserie et mobilier</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🎨</div>
                    <h3>Peinture & Décoration</h3>
                    <p>Services de peinture et décoration</p>
                </div>
                <div class="service-card">
                    <div class="service-icon">🔧</div>
                    <h3>Installation</h3>
                    <p>Installation d'appareils ménagers et mobilier</p>
                </div>
            </div>
            
            <div class="why-choose">
                <h3>Pourquoi choisir Clic & Fixe Bricolage?</h3>
                <ul class="benefits-list">
                    <li>Artisans spécialisés et expérimentés</li>
                    <li>Service rapide et à temps</li>
                    <li>Prix abordables et transparents</li>
                    <li>Garantie sur tous les services</li>
                    <li>Disponibles toute la semaine</li>
                </ul>
            </div>
            
            <p class="bio-text">
                Contactez-nous dès maintenant pour une consultation gratuite et un devis! Nous sommes là pour rendre votre maison plus confortable et plus sûre.
            </p>
        </section>
        
        <div class="contact-info">
            <h3>Prêt à réparer?</h3>
            <p>Appelez-nous au <strong>XX-XX-XX-XX-XX</strong> ou</p>
            <a href="#contact" class="btn">Demander un devis gratuit</a>
        </div>
    </div>

    <footer>
        <div class="container">
            <p>© 2023 Clic & Fixe Bricolage. Tous droits réservés.</p>
        </div>
    </footer>
</body>
</html>
