# BenmaxKing Online shop
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome to My Shop</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="cart.html">🛒 Cart (<span id="cart-count">0</span>)</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Affordable Products, Fast Delivery!</h2>
    <p>Shop electronics, fashion, and more.</p>
    <a href="products.html" class="btn">Shop Now</a>
  </section>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Products - My Shop</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Products</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="cart.html">🛒 Cart (<span id="cart-count">0</span>)</a>
    </nav>
  </header>

  <input type="text" id="search" placeholder="Search products..." onkeyup="searchProducts()">

  <div id="product-list" class="grid">
    <!-- Product 1 -->
    <div class="product">
      <img src="images/product1.jpg" alt="Smartphone">
      <h2>Smartphone X</h2>
      <p>KES 12,000</p>
      <button onclick="addToCart('Smartphone X', 12000)">Add to Cart</button>
    </div>

   <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Shopping Cart</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Your Cart</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="cart.html">Cart</a>
    </nav>
  </header>

  <div id="cart-items"></div>
  <h2>Total: KES <span id="total">0</span></h2>
  <a id="checkout" class="btn" href="#">Checkout via WhatsApp</a>

  <script src="script.js"></script>
</body>
</html>

  </div>

  <script src="script.js"></script>
</body>
</html>

  <footer>
    <p>© 2025 MyShop. All rights reserved.</p>
  </footer>

  
</body>
</html>
