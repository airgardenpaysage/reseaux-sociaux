<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Air Garden</title>
    <style>
        :root {
            --bg-color: #0f172a;
            --card-bg: #1e293b;
            --text-color: #f8fafc;
            --accent-color: #38bdf8;
        }

        body {
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
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

        h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
            font-weight: 700;
        }

        p {
            font-size: 1rem;
            opacity: 0.8;
            margin-bottom: 30px;
        }

        .links {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .link-card {
            background-color: var(--card-bg);
            color: var(--text-color);
            text-decoration: none;
            padding: 18px;
            border-radius: 14px;
            font-weight: 600;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .link-card:hover {
            transform: scale(1.02);
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
        <h1>Air Garden</h1>
        <p>Bienvenue sur mon espace personnel</p>

        <div class="links">
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
