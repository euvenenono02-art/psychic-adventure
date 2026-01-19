<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anime Peak Moments</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <nav>
        <div class="logo">ANIME<span>PEAK</span></div>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
        </ul>
    </nav>

    <header class="hero">
        <div class="hero-content">
            <h1>UNLEASH THE POWER</h1>
            <p>The most badass moments in anime history, all in one place.</p>
            <a href="#moments" class="btn">Explore Moments</a>
        </div>
    </header>

    <section id="moments" class="grid-container">
        <div class="moment-card">
            <img src="https://via.placeholder.com/400x250" alt="Gohan SSJ2">
            <h3>Gohan Ascends</h3>
            <p>The moment Gohan let go and snapped against Cell.</p>
        </div>
        <div class="moment-card">
            <img src="https://via.placeholder.com/400x250" alt="Naruto Arrival">
            <h3>Naruto Arrives in Sage Mode</h3>
            <p>The ultimate entrance to save the Hidden Leaf.</p>
        </div>
        <div class="moment-card">
            <img src="https://via.placeholder.com/400x250" alt="Luffy Punch">
            <h3>Luffy vs Celestial Dragon</h3>
            <p>The punch that echoed through the Grand Line.</p>
        </div>
    </section>

</body>
</html>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background-color: #0b0b0b;
    color: white;
}

/* Navigation */
nav {
    display: flex;
    justify-content: space-between;
    padding: 20px 50px;
    background: #1a1a1a;
}

.logo span { color: #ff4d4d; }

nav ul { list-style: none; display: flex; }
nav ul li a { 
    color: white; 
    text-decoration: none; 
    margin-left: 20px;
    font-weight: bold;
}

/* Hero Section */
.hero {
    height: 60vh;
    background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                url('https://images.unsplash.com/photo-1578632292335-df3abbb0d586?q=80&w=1000');
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}

.btn {
    background: #ff4d4d;
    color: white;
    padding: 10px 25px;
    text-decoration: none;
    border-radius: 5px;
    transition: 0.3s;
}

.btn:hover { background: #cc0000; }

/* Grid */
.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 50px;
}

.moment-card {
    background: #1a1a1a;
    padding: 15px;
    border-bottom: 4px solid #ff4d4d;
}

.moment-card img { width: 100%; border-radius: 5px; }
