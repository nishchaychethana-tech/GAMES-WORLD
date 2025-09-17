# GAMES-WORLD<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Nishchay's Gaming World</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0d0d0d;
      color: #00ffcc;
      text-align: center;
    }
    header {
      padding: 40px;
      background: linear-gradient(90deg, #1a1a1a, #333);
    }
    h1 {
      font-size: 3em;
      margin: 0;
      color: #00ffcc;
      text-shadow: 0 0 10px #00ffcc;
    }
    .games {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 40px;
      flex-wrap: wrap;
    }
    .game-card {
      background: #1a1a1a;
      border: 2px solid #00ffcc;
      border-radius: 12px;
      padding: 20px;
      width: 250px;
      transition: transform 0.3s;
    }
    .game-card:hover {
      transform: scale(1.05);
    }
    .game-card img {
      width: 100%;
      border-radius: 8px;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 20px;
      background: #00ffcc;
      color: #000;
      text-decoration: none;
      font-weight: bold;
      border-radius: 8px;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #00cc99;
    }
  </style>
</head>
<body>
  <header>
    <h1>🎮 Nishchay's Gaming World 🎮</h1>
    <p>Welcome to my gaming hub!</p>
  </header>

  <section class="games">
    <div class="game-card">
      <img src="https://www.youtube.com/watch?v=xv3wFGGeIsIpp=ygURZ3RhIGZ1bGwgZ2FtZXBsYXk%3D" alt="GTA V">
      <h3>GTA V</h3>
      <p>Open-world action and crazy adventures.</p>
    </div>
    <div class="game-card">
      <img src="https://upload.wikimedia.org/wikipedia/en/5/5e/Minecraft_cover.png" alt="Minecraft">
      <h3>Minecraft</h3>
      <p>Build, survive, and explore infinite worlds.</p>
    </div>
    <div class="game-card">
      <img src="https://upload.wikimedia.org/wikipedia/en/d/d7/Fortnite_cover_art.jpg" alt="Fortnite">
      <h3>Fortnite</h3>
      <p>Battle Royale with friends and cool skins.</p>
    </div>
  </section>

  <a class="btn" href="https://www.youtube.com" target="_blank">Watch Gaming Videos</a>
</body>
</html>
