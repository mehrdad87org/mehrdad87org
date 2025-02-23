<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Profiles</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@900&display=swap" rel="stylesheet">
    <style>
        body {
            background: #0a0a0a;
            color: #fff;
            font-family: 'Orbitron', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .neon-text {
            font-size: 6rem;
            text-align: center;
            animation: glow 1.5s infinite alternate;
        }
        @keyframes glow {
            0% { text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #00e6e6, 0 0 40px #00e6e6, 0 0 50px #00e6e6; }
            100% { text-shadow: 0 0 20px #fff, 0 0 30px #fff, 0 0 40px #00e6e6, 0 0 50px #00e6e6, 0 0 60px #00e6e6; }
        }
        .social-icons {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }
        .social-icon {
            width: 150px;
            height: 150px;
            padding: 20px;
            border-radius: 25px;
            transition: transform 0.3s ease, filter 0.3s ease;
            border: 4px solid transparent;
        }
        .social-icon:hover {
            transform: scale(1.4);
            filter: drop-shadow(0 0 20px currentColor) drop-shadow(0 0 40px currentColor);
        }
        .telegram {
            color: #0088cc;
            border-color: #0088cc;
        }
        .instagram {
            color: #e1306c;
            border-color: #e1306c;
        }
        .github {
            color: #6e5494;
            border-color: #6e5494;
        }
        .whatsapp {
            color: #25d366;
            border-color: #25d366;
        }
        .linkedin {
            color: #00a0dc;
            border-color: #00a0dc;
        }
        .email {
            color: #ff4444;
            border-color: #ff4444;
        }
    </style>
</head>
<body>
    <div class="social-icons">
        <a href="https://t.me/mehrdad87org" target="_blank">
            <img src="https://img.icons8.com/?size=100&id=k4jADXhS5U1t&format=png&color=000000" class="social-icon telegram" alt="Telegram">
        </a>
        <a href="https://wa.link/78c7u1" target="_blank">
            <img src="https://img.icons8.com/?size=100&id=A1JUR9NRH7sC&format=png&color=000000" class="social-icon whatsapp" alt="WhatsApp">
        </a>
        <a href="https://github.com/mehrdad87org" target="_blank">
            <img src="https://img.icons8.com/?size=100&id=LoL4bFzqmAa0&format=png&color=000000" class="social-icon github" alt="GitHub">
        </a>
        <a href="mailto:mehrdad87ourangg@gmail.com" target="_blank">
            <img src="https://img.icons8.com/?size=100&id=eFPBXQop6V2m&format=png&color=000000" class="social-icon email" alt="Email">
        </a>
        <a href="https://instagram.com/mehrdad_ourang87" target="_blank">
            <img src="https://img.icons8.com/?size=100&id=nj0Uj45LGUYh&format=png&color=000000" class="social-icon instagram" alt="Instagram">
        </a>
        <a href="https://www.linkedin.com/in/mehrdad-ourang-4204b734a" target="_blank">
            <img src="https://img.icons8.com/?size=100&id=MR3dZdlA53te&format=png&color=000000" class="social-icon linkedin" alt="LinkedIn">
        </a>
    </div>
</body>
</html>
