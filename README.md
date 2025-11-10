# Hand-made-india-
Its like flipcart 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Handmade India</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #fff8f0;
      color: #333;
    }

    header {
      background-color: #e67300;
      color: white;
      padding: 20px 50px;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
      letter-spacing: 2px;
    }

    nav {
      background: #ffcc80;
      padding: 10px;
      text-align: center;
    }

    nav a {
      text-decoration: none;
      color: #333;
      margin: 0 15px;
      font-weight: 500;
    }

    nav a:hover {
      color: #e67300;
    }

    .hero {
      background-image: url('https://images.unsplash.com/photo-1599586120429-58d722a3d497');
      background-size: cover;
      background-position: center;
      color: white;
      text-align: center;
      padding: 120px 20px;
    }

    .hero h1 {
      font-size: 3em;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.6);
    }

    .section {
      padding: 60px 20px;
      text-align: center;
    }

    .section h2 {
      color: #e67300;
      margin-bottom: 30px;
      font-size: 2em;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }

    .product {
      background: white;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s;
    }

    .product:hover {
      transform: scale(1.05);
    }

    .product img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .product h3 {
      padding: 15px;
      font-size: 1.2em;
    }

    footer {
      background: #e67300;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }

    footer p {
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>🧵 Handmade India</header>

  <nav>
    <a href="#home">Home</a>
    <a href="#crafts">Crafts</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <section class="hero" id="home">
    <h1>Celebrate Indian Artisans & Handmade Beauty</h1>
  </section>

  <section class="section" id="crafts">
    <h2>Our Best Handmade Crafts</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1601049676869-702ea24cfd14" alt="Handmade Pottery">
        <h3>Handmade Clay Pottery</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1565373679713-3f8e5c2bbfd8" alt="Handmade Jewelry">
        <h3>Traditional Jewelry</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1580460610862-37a10866c9c8" alt="Handwoven Fabrics">
        <h3>Handwoven Fabrics</h3>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1603279527226-6b6bdf2c46d4" alt="Wooden Crafts">
        <h3>Wooden Art Pieces</h3>
      </div>
    </div>
  </section>

  <section class="section" id="about">
    <h2>About Handmade India</h2>
    <p style="max-width:700px; margin:auto; line-height:1.8;">
      Handmade India is a platform dedicated to supporting local artisans and traditional crafts.
      We connect rural creativity with the modern world — each product tells a story of skill, passion,
      and Indian heritage. Join us in preserving the culture of handcrafting.
    </p>
  </section>

  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Email: <b>support@handmadeindia.in</b></p>
    <p>Instagram: <b>@handmade.india</b></p>
  </section>

  <footer>
    <p>© 2025 Handmade India | Crafted with ❤️ in India</p>
  </footer>

</body>
</html>
