<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Neon RGB Border</title>
  <style>
    /* Container for the neon border */
    .neon-container {
      position: relative;
      padding: 20px;
      border: 4px solid transparent;
      border-radius: 15px;
      background: rgba(0, 0, 0, 0.8); /* Dark background for contrast */
      box-shadow: 0 0 20px rgba(255, 0, 0, 0.8), 0 0 40px rgba(0, 255, 0, 0.8), 0 0 60px rgba(0, 0, 255, 0.8);
      animation: neon-glow 3s linear infinite;
      overflow: hidden;
    }

    /* Neon border animation */
    @keyframes neon-glow {
      0% {
        box-shadow: 0 0 20px rgba(255, 0, 0, 0.8), 0 0 40px rgba(0, 255, 0, 0.8), 0 0 60px rgba(0, 0, 255, 0.8);
      }
      33% {
        box-shadow: 0 0 20px rgba(0, 255, 0, 0.8), 0 0 40px rgba(0, 0, 255, 0.8), 0 0 60px rgba(255, 0, 0, 0.8);
      }
      66% {
        box-shadow: 0 0 20px rgba(0, 0, 255, 0.8), 0 0 40px rgba(255, 0, 0, 0.8), 0 0 60px rgba(0, 255, 0, 0.8);
      }
      100% {
        box-shadow: 0 0 20px rgba(255, 0, 0, 0.8), 0 0 40px rgba(0, 255, 0, 0.8), 0 0 60px rgba(0, 0, 255, 0.8);
      }
    }

    /* Inner content styling */
    .neon-content {
      color: #fff;
      font-family: Arial, sans-serif;
      text-align: center;
    }

    /* Neon text glow */
    .neon-content h3 {
      color: #00ffcc;
      text-shadow: 0 0 5px #00ffcc, 0 0 10px #00ffcc, 0 0 20px #00ffcc, 0 0 40px #00ffcc;
    }

    /* Neon social icons */
    .neon-content img {
      border: 2px solid #00ffcc;
      border-radius: 10px;
      box-shadow: 0 0 10px #00ffcc, 0 0 20px #00ffcc;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .neon-content img:hover {
      transform: scale(1.2);
      box-shadow: 0 0 20px #00ffcc, 0 0 40px #00ffcc;
    }
  </style>
</head>
<body>
  <div class="neon-container">
    <div class="neon-content">
      <h3 align="center">A passionate frontend developer from India</h3>

      <p align="left"> <img src="https://komarev.com/ghpvc/?username=mehrdad87org&label=Profile%20views&color=0e75b6&style=flat" alt="mehrdad87org" /> </p>

      <p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=mehrdad87org" alt="mehrdad87org" /></a> </p>

      <img align="right" alt="..." width="200" src="https://media2.giphy.com/media/oFYKw5OTZBZzVONpUh/giphy.webp?cid=790b7611p0gv3ecxbm5g3s06yud1idy22g8d2t1yvutuae4w&ep=v1_gifs_search&rid=giphy.webp&ct=g">

      <p align="left"> <a href="https://twitter.com/" target="blank"><img src="https://img.shields.io/twitter/follow/?logo=twitter&style=for-the-badge" alt="" /></a> </p>

      <h3 align="left">Languages and Tools:</h3>
      <p align="left">
        <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a>
        <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a>
        <a href="https://www.qt.io/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Qt_logo_2016.svg" alt="qt" width="40" height="40"/> </a>
      </p>

      <p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=mehrdad87org&show_icons=true&locale=en&layout=compact" alt="mehrdad87org" /></p>

      <p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=mehrdad87org&show_icons=true&locale=en" alt="mehrdad87org" /></p>

      <p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=mehrdad87org&" alt="mehrdad87org" /></p>

      <h3 align="left">My Social Profiles:</h3>
      <p align="left">
        <a href="https://t.me/mehrdad87org" target="_blank"><img src="https://img.icons8.com/?size=100&id=k4jADXhS5U1t&format=png&color=000000" alt="Telegram" width="50" height="50" /></a>
        <a href="https://wa.link/78c7u1" target="_blank"><img src="https://img.icons8.com/?size=100&id=A1JUR9NRH7sC&format=png&color=000000" alt="WhatsApp" width="50" height="50" /></a>
        <a href="https://github.com/mehrdad87org" target="_blank"><img src="https://img.icons8.com/?size=100&id=LoL4bFzqmAa0&format=png&color=000000" alt="GitHub" width="50" height="50" /></a>
        <a href="mailto:mehrdad87ourangg@gmail.com" target="_blank"><img src="https://img.icons8.com/?size=100&id=eFPBXQop6V2m&format=png&color=000000" alt="Email" width="50" height="50" /></a>
        <a href="https://instagram.com/mehrdad_ourang87" target="_blank"><img src="https://img.icons8.com/?size=100&id=nj0Uj45LGUYh&format=png&color=000000" alt="Instagram" width="50" height="50" /></a>
        <a href="https://www.linkedin.com/in/mehrdad-ourang-4204b734a" target="_blank"><img src="https://img.icons8.com/?size=100&id=MR3dZdlA53te&format=png&color=000000" alt="LinkedIn" width="50" height="50" /></a>
      </p>
    </div>
  </div>
</body>
</html>
