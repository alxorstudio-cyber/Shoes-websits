# Shoes-websits
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        nav {
            background-color: #444;
            padding: 0.5rem;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x400?text=Shoes+Hero+Image');
            background-size: cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        .products {
            display: flex;
            justify-content: space-around;
            padding: 2rem;
            flex-wrap: wrap;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            width: 300px;
            margin: 1rem;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Shoes</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="home" class="hero">
        <h2>Discover Comfort and Style</h2>
    </section>
    <section id="products" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Sneakers" alt="Sneakers">
            <h3>Sneakers</h3>
            <p>Comfortable and stylish sneakers for everyday wear.</p>
            <p>$50</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Boots" alt="Boots">
            <h3>Boots</h3>
            <p>Durable boots for all terrains.</p>
            <p>$80</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300x200?text=Sandals" alt="Sandals">
            <h3>Sandals</h3>
            <p>Lightweight sandals for summer.</p>
            <p>$30</p>
        </div>
    </section>
    <section id="about">
        <h2>About Us</h2>
        <p>We offer high-quality shoes designed for comfort, style, and durability. No matter your lifestyle, we have the perfect pair for you.</p>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: info@shoes.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>
    <footer>
        <p>&copy; 2023 Shoes. All rights reserved.</p>
    </footer>
</body>
</html>
