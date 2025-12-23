# cyberhacks
cyber hack is the
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gaming Hub</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Navbar -->
  <header class="navbar">
    <h1 class="logo">🎮 GamingHub</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Games</a>
      <a href="#">Tournaments</a>
      <a href="#">Community</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h2>Welcome to the Ultimate Gaming Hub</h2>
    <p>Play. Compete. Connect.</p>
    <button>Explore Games</button>
  </section>

  <!-- Games Section -->
  <section class="games">
    <h2>🔥 Popular Games</h2>

    <div class="game-grid">
      <div class="game-card">
        <img src="https://via.placeholder.com/300x180" alt="Game 1">
        <h3>Battle Arena</h3>
        <p>Action | Multiplayer</p>
      </div>

      <div class="game-card">
        <img src="https://via.placeholder.com/300x180" alt="Game 2">
        <h3>Racing X</h3>
        <p>Racing | Online</p>
      </div>

      <div class="game-card">
        <img src="https://via.placeholder.com/300x180" alt="Game 3">
        <h3>Zombie Survival</h3>
        <p>Horror | Co-op</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 GamingHub | All Rights Reserved</p>
  </footer>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: #0f172a;
  color: #fff;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  background: #020617;
}

.logo {
  color: #38bdf8;
}

.navbar a {
  margin-left: 20px;
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

.navbar a:hover {
  color: #38bdf8;
}

/* Hero */
.hero {
  text-align: center;
  padding: 80px 20px;
  background: linear-gradient(135deg, #020617, #1e293b);
}

.hero h2 {
  font-size: 2.5rem;
}

.hero p {
  margin: 15px 0;
  font-size: 1.2rem;
}

.hero button {
  padding: 12px 30px;
  border: none;
  background: #38bdf8;
  color: #000;
  font-size: 1rem;
  cursor: pointer;
  border-radius: 5px;
}

.hero button:hover {
  background: #0ea5e9;
}

/* Games Section */
.games {
  padding: 50px;
  text-align: center;
}

.games h2 {
  margin-bottom: 30px;
}

.game-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

.game-card {
  background: #020617;
  border-radius: 10px;
  overflow: hidden;
  transition: transform 0.3s;
}

.game-card img {
  width: 100%;
}

.game-card h3 {
  margin: 10px 0;
}

.game-card p {
  color: #94a3b8;
  margin-bottom: 15px;
}

.game-card:hover {
  transform: scale(1.05);
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: #020617;
  color: #94a3b8;
}

</body>
</html>
