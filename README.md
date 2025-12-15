# cosmic-gamer-site
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Cosmic Gamer Hub</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(circle at top, #1b1f3b, #000);
      color: #fff;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: url("https://images.unsplash.com/photo-1446776811953-b23d57bd21aa") center/cover;
      box-shadow: inset 0 0 100px #000;
    }

    header h1 {
      font-size: 3.5rem;
      color: #00f6ff;
      text-shadow: 0 0 20px #00f6ff;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 20px;
      background: #0b0f2b;
    }

    nav a {
      color: #00f6ff;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #fff;
      text-shadow: 0 0 10px #00f6ff;
    }

    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(0, 246, 255, 0.3);
      border-radius: 15px;
      padding: 25px;
      transition: 0.3s;
      box-shadow: 0 0 20px rgba(0, 246, 255, 0.1);
    }

    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 0 30px rgba(0, 246, 255, 0.6);
    }

    .card h3 {
      color: #00f6ff;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #050816;
      color: #777;
      font-size: 0.9rem;
    }

    .play-btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 30px;
      border-radius: 30px;
      background: linear-gradient(45deg, #00f6ff, #7a00ff);
      color: #000;
      font-weight: bold;
      text-decoration: none;
      box-shadow: 0 0 20px #00f6ff;
      transition: 0.3s;
    }

    .play-btn:hover {
      box-shadow: 0 0 40px #7a00ff;
      transform: scale(1.05);
    }
  </style>
</head>

<body>

<header>
  <h1>🌌 Cosmic Gamer Hub</h1>
  <p>Level up beyond the stars</p>
  <a href="#games" class="play-btn">Start Gaming</a>
</header>

<nav>
  <a href="#games">Games</a>
  <a href="#news">News</a>
  <a href="#community">Community</a>
</nav>

<section id="games">
  <h2>🎮 Featured Games</h2>
  <div class="cards">
    <div class="card">
      <h3>Galaxy Raiders</h3>
      <p>Fast-paced space battles with neon weapons and alien bosses.</p>
    </div>
    <div class="card">
      <h3>Astro Survival</h3>
      <p>Survive on hostile planets and build your interstellar base.</p>
    </div>
    <div class="card">
      <h3>Star Drift</h3>
      <p>High-speed cosmic racing across asteroid belts.</p>
    </div>
  </div>
</section>

<section id="news">
  <h2>🛰️ Space News</h2>
  <p>New updates, tournaments, and cosmic events coming soon!</p>
</section>

<section id="community">
  <h2>👾 Community</h2>
  <p>Join our space crew, share clips, and squad up with other gamers.</p>
</section>

<footer>
  © 2025 Cosmic Gamer Hub | made by audree✨
</footer>

</body>
</html>
