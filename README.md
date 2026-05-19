<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ClickBazaar</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      background:#0a0a0a;
      color:white;
    }

    nav{
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:20px 50px;
      background:#111;
      border-bottom:1px solid #333;
    }

    nav h1{
      color:gold;
      font-size:32px;
    }

    nav ul{
      display:flex;
      gap:20px;
      list-style:none;
    }

    nav a{
      text-decoration:none;
      color:white;
    }

    .hero{
      text-align:center;
      padding:100px 20px;
    }

    .hero h2{
      font-size:60px;
      margin-bottom:20px;
      color:gold;
    }

    .hero p{
      color:#ccc;
      font-size:20px;
    }

    .btn{
      margin-top:30px;
      padding:15px 35px;
      border:none;
      background:gold;
      color:black;
      font-size:18px;
      border-radius:10px;
      cursor:pointer;
      font-weight:bold;
    }

    .products{
      padding:50px;
    }

    .products h3{
      text-align:center;
      font-size:40px;
      margin-bottom:40px;
      color:gold;
    }

    .product-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:30px;
    }

    .card{
      background:#161616;
      border-radius:20px;
      overflow:hidden;
      transition:0.3s;
      border:1px solid #333;
    }

    .card:hover{
      transform:translateY(-10px);
      border-color:gold;
    }

    .card img{
      width:100%;
      height:250px;
      object-fit:cover;
    }

    .card-content{
      padding:20px;
    }

    .card-content h4{
      margin-bottom:10px;
    }

    .price{
      color:gold;
      font-size:22px;
      margin-bottom:15px;
    }

    footer{
      text-align:center;
      padding:30px;
      border-top:1px solid #333;
      margin-top:50px;
      color:#888;
    }
  </style>
</head>

<body>

  <nav>
    <h1>ClickBazaar</h1>

    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Products</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <section class="hero">
    <h2>Luxury Shopping Experience</h2>
    <p>Welcome to ClickBazaar Premium Online Store</p>

    <button class="btn">Shop Now</button>
  </section>

  <section class="products">

    <h3>Trending Products</h3>

    <div class="product-grid">

      <div class="card">
        <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30" />
        
        <div class="card-content">
          <h4>Luxury Watch</h4>
          <p class="price">₹4,999</p>
          <button class="btn">Buy Now</button>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" />
        
        <div class="card-content">
          <h4>Premium Shoes</h4>
          <p class="price">₹3,499</p>
          <button class="btn">Buy Now</button>
        </div>
      </div>

      <div class="card">
        <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e" />
        
        <div class="card-content">
          <h4>Wireless Headphones</h4>
          <p class="price">₹2,999</p>
          <button class="btn">Buy Now</button>
        </div>
      </div>

    </div>

  </section>

  <footer>
    © 2026 ClickBazaar | All Rights Reserved
  </footer>

</body>
</html>
