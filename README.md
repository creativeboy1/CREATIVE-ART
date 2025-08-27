<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CREATIVE ART</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }
    header {
      background: black;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #333;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background: #575757;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 15px;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }
    footer {
      text-align: center;
      padding: 15px;
      background: #222;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>CREATIVE ART</h1>
    <p>Gallery of Paintings, String Art, Drawings & More</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#shop">Shop</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home" style="padding:20px; text-align:center;">
    <h2>Welcome to Creative Art</h2>
    <p>Discover unique and original artworks that bring creativity to life.</p>
  </section>

  <section id="gallery" class="gallery">
    <img src="art1.jpg" alt="Artwork 1">
    <img src="art2.jpg" alt="Artwork 2">
    <img src="art3.jpg" alt="Artwork 3">
    <img src="art4.jpg" alt="Artwork 4">
  </section>

  <section id="about" style="padding:20px;">
    <h2>About Me</h2>
    <p>I am a passionate artist creating unique artworks including painting, string art, wall designs, and drawings. Each piece tells a story and brings emotions to life.</p>
  </section>

  <section id="shop" style="padding:20px;">
    <h2>Shop Artworks</h2>
    <p>Browse and purchase my original artworks. (Payment integration can be added later)</p>
  </section>

  <section id="contact" style="padding:20px;">
    <h2>Contact Me</h2>
    <p>Email: yourname@gmail.com</p>
    <p>Phone: +123456789</p>
    <p>Follow me on Instagram, TikTok, and Facebook!</p>
  </section>

  <footer>
    <p>© 2025 Creative Art. All rights reserved.</p>
  </footer>
</body>
</html> CREATIVE-ART
