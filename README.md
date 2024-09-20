<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Natus Vincere Clothing</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem;
        }
        header h1 {
            margin: 0;
        }
        nav {
            text-align: center;
            padding: 1rem;
            background-color: #555;
        }
        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }
        .banner {
            background-image: url('banner-image.jpg');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .banner h2 {
            font-size: 3rem;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem;
        }
        .product {
            background-color: #fff;
            margin: 15px;
            padding: 15px;
            border: 1px solid #ddd;
            width: 300px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: #fff;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Natus Vincere Clothing</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>

    <section class="banner">
        <h2>Exclusive Limited Edition T-Shirts</h2>
    </section>

    <section class="products" id="products">
        <div class="product">
            <img src="stuicism.jpg" alt="STUICISM T-shirt">
            <h3>STUICISM T-shirt</h3>
            <p>Bahan: Cotton Combed 20s<br>Sablon: Plastisol<br>Style: T-shirt</p>
            <p><strong>Hanya 50pcs - Pre-order Sekarang!</strong></p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="navi-not-nazi.jpg" alt="NAVI NOT N**I T-shirt">
            <h3>NAVI NOT N**I T-shirt</h3>
            <p>Bahan: Cotton Combed 20s<br>Sablon: Plastisol<br>Style: T-shirt</p>
            <p><strong>Hanya 50pcs - Pre-order Sekarang!</strong></p>
            <button>Buy Now</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Natus Vincere Clothing. All rights reserved.</p>
    </footer>
</body>
</html>
