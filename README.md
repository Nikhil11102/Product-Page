HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Smart Light Bulb Product Page</title>
  <link rel="stylesheet" href=".css">
</head>
<body>
  <header>
   <h1>Smart Lights</h1>
  </header>

  <section class="product-container">
    <div class="product-image">
      <img src="https://smartify.in/wp-content/uploads/2021/05/DigiLife-Color-Bulb.jpg">
    </div>
    <div class="product-details">
      <h2>Smart LED Light Bulb</h2>
      <p class="price">₹999</p>
      <p class="description">Transform your home with our energy-efficient Smart LED Light Bulb. Easily control brightness, color, and more from your phone. Compatible with Alexa and Google Assistant!</p>

      <h3>Features:</h3>
        <li>RGB Color Changing</li>
        <li>Smartphone Control</li>
        <li>Voice Command Support</li>
        <li>Energy Efficient</li>
        <li>Easy Setup & Install</li>

      <div class="product-actions">
        <button class="buy-btn">Buy Now</button>
        <button class="add-to-cart-btn">Add to Cart</button>
      </div>
    </div>
  </section>
</body>
</html>


CSS
 body {
    font-family: Arial, sans-serif;
    background-color: rgba(0, 0, 0, 0);
    color: rgb(0, 0, 0);
  }
  
  header {
    background-color: #4CAF50;
    padding: 10px 0;
    text-align: center;
  }
  
  .product-container {
    text-align: center;
    margin: 40px;
  }
  
  .product-image img {
    width: 300px;
    height: 300px;
    border-radius: 80px;
  }
  
  .product-details {
    text-align: center;
  }
  
  .price {
    font-size: 1.5em;
    color: #4CAF50;
    margin-bottom: 10px;
  }
  
  h3 {
    font-size: 20px;
    margin-bottom: 10px;
  }
  
  .product-actions {
    text-align: center;
    margin:20px;
  }
  
  .buy-btn, .add-to-cart-btn {
    background-color: #4CAF50;
    color: white;
    font-size: 20px;
  }
  
  .buy-btn:hover, .add-to-cart-btn:hover {
    background-color: #45a049;
  }
  
  footer {
    background-color: #303030;
    color: white;
    text-align: center;
  }
  
