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

function pauseMusic() {
  music.pause();
}
</script>

</body>
</html>
