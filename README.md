# psychic-adventure
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Aux Call & Chat – Nature Connect</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: linear-gradient(to bottom, #4facfe, #00f2fe);
  color: white;
}

/* HERO SECTION */
.hero {
  height: 100vh;
  background: url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee") center/cover;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  backdrop-filter: brightness(0.7);
}

.hero-content {
  background: rgba(0,0,0,0.6);
  padding: 40px;
  border-radius: 15px;
}

.hero h1 {
  font-size: 3em;
}

.hero p {
  font-size: 1.2em;
}

/* BUTTONS */
.btn {
  background: #00ff99;
  color: black;
  padding: 12px 20px;
  border-radius: 30px;
  border: none;
  cursor: pointer;
  font-size: 16px;
  margin: 10px;
}

.btn:hover {
  background: #00cc77;
}

/* FEATURES */
.features {
  padding: 60px;
  background: #1b4332;
  text-align: center;
}

.features h2 {
  margin-bottom: 30px;
}

.feature-box {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.feature {
  background: rgba(255,255,255,0.15);
  padding: 20px;
  margin: 15px;
  border-radius: 15px;
  width: 250px;
}

/* MUSIC PLAYER */
.music-box {
  position: fixed;
  bottom: 20px;
  right: 20px;
  background: rgba(0,0,0,0.8);
  padding: 15px;
  border-radius: 12px;
  box-shadow: 0 0 15px #00ff99;
}

.music-box button {
  background: #00ff99;
  border: none;
  padding: 5px 10px;
  cursor: pointer;
}

/* FOOTER */
footer {
  background: #081c15;
  text-align: center;
  padding: 20px;
}
</style>
</head>

<body>

<!-- HERO -->
<section class="hero">
  <div class="hero-content">
    <h1>Connect Through Nature 🌍</h1>
    <p>Free calls & chat inspired by peace and harmony</p>
    <button class="btn">Start Chat</button>
    <button class="btn">Voice Call</button>
  </div>
</section>

<!-- FEATURES -->
<section class="features">
  <h2>Why Choose Aux Call & Chat?</h2>
  <div class="feature-box">
    <div class="feature">🌿 Calm & Natural Design</div>
    <div class="feature">📞 Free Voice Calls</div>
    <div class="feature">💬 Instant Messaging</div>
    <div class="feature">🌍 Global Connection</div>
  </div>
</section>

<!-- MUSIC -->
<div class="music-box">
  🎵 Nature Music<br>
  <button onclick="playMusic()">▶ Play</button>
  <button onclick="pauseMusic()">⏸ Pause</button>
</div>

<audio id="bgmusic" loop>
  <source src="nature-music.mp3" type="audio/mpeg">
</audio>

<footer>
  © 2024 Aux Call & Chat – Connecting the World
</footer>

<script>
const music = document.getElementById("bgmusic");

function playMusic() {
  music.play();
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Health & Tips</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #d0f0c0, #a0e1a0);
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #2e7d32;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      margin: 15px 0;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #1b5e20;
      font-weight: bold;
    }

    nav a:hover {
      color: #ffffff;
    }

    main {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }

    .tip {
      background-color: rgba(255,255,255,0.9);
      border-radius: 12px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 2px 2px 12px rgba(0,0,0,0.1);
      display: flex;
      align-items: center;
      gap: 15px;
    }

    .tip img {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      object-fit: cover;
    }

    .tip h2 {
      margin: 0;
      color: #2e7d32;
    }

    .tip p {
      margin: 5px 0 0;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #2e7d32;
      color: white;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Health & Tips</h1>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="health.html">Health & Tips</a>
    <a href="contact.html">Contact</a>
  </nav>

  <main>
    <div class="tip">
      <img src="images/water.png" alt="Drink Water">
      <div>
        <h2>Stay Hydrated</h2>
        <p>Drink at least 8 glasses of water a day to keep your body functioning properly and maintain energy levels.</p>
      </div>
    </div>

    <div class="tip">
      <img src="images/fruits.png" alt="Eat Healthy">
      <div>
        <h2>Eat a Balanced Diet</h2>
        <p>Include fruits, vegetables, lean proteins, and whole grains in your meals for proper nutrition.</p>
      </div>
    </div>

    <div class="tip">
      <img src="images/exercise.png" alt="Exercise">
      <div>
        <h2>Exercise Regularly</h2>
        <p>Engage in at least 30 minutes of physical activity every day to improve strength, mood, and overall health.</p>
      </div>
    </div>

    <div class="tip">
      <img src="images/sleep.png" alt="Sleep">
      <div>
        <h2>Get Enough Sleep</h2>
        <p>Aim for 7-9 hours of sleep each night to help your body recover and stay focused throughout the day.</p>
      </div>
    </div>
  </main>

  <footer>
    &copy; 2026 YourWebsite | Healthy Living Tips
  </footer>
</body>
</html>

function pauseMusic() {
  music.pause();
}
</script>

</body>
</html>
