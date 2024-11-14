# Oceans Music
Oceans music repository
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Artist Name - Official Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="logo">
      <h1>Artist Name</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#music">Music</a></li>
        <li><a href="#tour">Tour</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section (Main landing page) -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h2>Welcome to My Official Website</h2>
      <p>Listen to my latest track and explore my music.</p>
      <a href="#music" class="cta-button">Listen Now</a>
    </div>
  </section>

  <!-- Music Section -->
  <section id="music">
    <h2>Latest Music</h2>
    <div class="music-player">
      <!-- Spotify Embed (or another service like SoundCloud) -->
      <iframe src="https://open.spotify.com/embed/track/tr
      /* Global styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

a {
  text-decoration: none;
  color: inherit;
}

/* Header */
header {
  background: #333;
  color: #fff;
  padding: 20px;
}

header .logo h1 {
  display: inline-block;
}

header nav ul {
  list-style: none;
  float: right;
}

header nav ul li {
  display: inline;
  margin: 0 15px;
}

header nav ul li a {
  color: white;
  font-weight: bold;
  font-size: 1.1em;
}

/* Hero Section */
.hero {
  background-image: url('hero-image.jpg'); /* Replace with your image */
  background-size: cover;
  text-align: center;
  color: white;
  padding: 100px 0;
}

.hero-content h2 {
  font-size: 3em;
  margin-bottom: 10px;
}

.cta-button {
  background-color: #333;
  color: white;
  padding: 15px 30px;
  font-size: 1.2em;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.cta-button:hover {
  background-color: #555;
}

/* Music Section */
#music {
  padding: 50px;
  background-color: #fff;
  text-align: center;
}

#music h2 {
  font-size: 2em;
  margin-bottom: 20px;
}

/* Tour Section */
#tour {
  background-color: #f8f8f8;
  padding: 50px;
}

#tour ul {
  list-style: none;
}

#tour ul li {
  font-size: 1.2em;
  margin-bottom: 10px;
}

/* About Section */
#about {
  padding: 50px;
  background-color: #fff;
}

/* Contact Section */
#contact {
  background-color: #f8f8f8;
  padding: 50px;
}

#contact form input, #contact form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

#contact form button {
  padding: 10px 20px;
  background-color: #333;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

#contact form button:hover {
  background-color: #555;
}

/* Footer */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 20px;
}

