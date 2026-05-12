<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mes Réseaux Sociaux</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #f8fafc;
            --accent-color: #38bdf8;
            --hover-color: #7dd3fc;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 400px;
            text-align: center;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 3px solid var(--accent-color);
            margin-bottom: 15px;
            object-fit: cover;
        }

        h1 {
            font-size: 1.5rem;
            margin-bottom: 5px;
        }

        p {
            font-size: 0.9rem;
            opacity: 0.8;
            margin-bottom: 30px;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .link-card {
            background-color: var(--card-bg);
            color: var(--text-color);
            text-decoration: none;
            padding: 15px;
            border-radius: 12px;
            font-weight: 600;
            transition: all 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .link-card:hover {
            transform: translateY(-3px);
            background-color: var(--accent-color);
            color: var(--bg-color);
        }

        footer {
            margin-top: 50px;
            font-size: 0.8rem;
            opacity: 0.5;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Ta photo ou un avatar -->
        <img src="https://via.placeholder.com/100" alt="Avatar" class="profile-img">
        
        <h1>Ton Air / Garden</h1>
        <p>Bienvenue sur mon espace personnel</p>

        <div class="links">
            <!-- Remplace les # par tes vrais liens -->
            <a href="https://www.instagram.com/airgarden.fr/?hl=fr" class="link-card" target="_blank">Instagram</a>           
            <a href="https://www.linkedin.com/in/air-garden-5b4390119/" class="link-card" target="_blank">LinkedIn</a>
            <a href="https://www.tiktok.com/@airgarden_paysage?lang=fr" class="link-card" target="_blank">TikTok</a>
            <a href="https://www.youtube.com/@airgarden_paysage" class="link-card" target="_blank">YouTube</a>
            <a href="mailto:rg.airgarden@gmail.com@gmail.com" class="link-card">Contact Email</a>
        </div>
    </div>

    <footer>© 2026 - Créé avec passion</footer>

</body>
</html>


