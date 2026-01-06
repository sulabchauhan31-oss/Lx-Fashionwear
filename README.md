# Lx-Fashionwear<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>UrbanWear | Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
    body { background: #ffffff; color: #111; }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
      border-bottom: 1px solid #eee;
    }

    header h1 { font-weight: 700; letter-spacing: 2px; }

    nav a {
      margin-left: 30px;
      text-decoration: none;
      color: #111;
      font-weight: 500;
    }

    .hero {
      height: 90vh;
      background: url('https://images.unsplash.com/photo-1521335629791-ce4aec67dd47') center/cover no-repeat;
      display: flex;
      align-items: center;
      padding: 60px;
    }

    .hero-content {
      max-width: 500px;
      background: rgba(255,255,255,0.9);
      padding: 40px;
      border-radius: 10px;
    }

    .hero-content h2 { font-size: 42px; margin-bottom: 20px; }
    .hero-content p { margin-bottom: 30px; color: #444; }

    .hero-content button {
      padding: 12px 30px;
      border: none;
      background: #111;
      color: #fff;
      font-size: 16px;
      cursor: pointer;
      border-radius: 30px;
    }

    section { padding: 80px 60px; }

    .section-title {
      text-align: center;
      margin-bottom: 50px;
      font-size: 32px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .product {
      border: 1px solid #eee;
      border-radius: 10px;
      overflow: hidden;
      text-align: center;
    }

    .product img { width: 100%; height: 300px; object-fit: cover; }
    .product h3 { margin: 15px 0 5px; }
    .product p { color: #666; margin-bottom: 15px; }

    footer {
      background: #111;
      color: #fff;
      padding: 40px 60px;
      text-align: center;
    }

    footer p { color: #aaa; margin-top: 10px; }

    @media (max-width: 768px) {
      header { padding: 20px; }
      section { padding: 60px 20px; }
      .hero { padding: 20px; }
      .hero-content h2 { font-size: 32px; }
    }
  </style>
</head>
<body>

  <header>
    <h1>URBANWEAR</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Shop</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <div class="hero-content">
      <h2>New Season. New Style.</h2>
      <p>Discover premium streetwear designed for comfort, confidence, and everyday style.</p>
      <button>Shop Now</button>
    </div>
  </div>

  <section>
    <h2 class="section-title">Featured Collection</h2>
    <div class="products">
      <div class="product">
        <img src="https://images.unsplash.com/photo-1520975916090-3105956dac38" alt="T-shirt">
        <h3>Classic Tee</h3>
        <p>$29.99</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1503342217505-b0a15ec3261c" alt="Hoodie">
        <h3>Urban Hoodie</h3>
        <p>$59.99</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1525171254930-643fc658b64b" alt="Jacket">
        <h3>Street Jacket</h3>
        <p>$89.99</p>
      </div>
    </div>
  </section>

  <footer>
    <h2>URBANWEAR</h2>
    <p>© 2026 UrbanWear. All rights reserved.</p>
  </footer>

</body>
</html>
