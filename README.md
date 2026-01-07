<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Watch Collection</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .product h3 {
            margin: 10px 0;
        }
        .product p {
            color: #666;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Timeless Watches</h1>
        <p>Explore our collection of premium timepieces</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#analog">Analog</a>
        <a href="#digital">Digital</a>
        <a href="#smart">Smart</a>
        <a href="#contact">Contact</a>
    </nav>
    <main>
        <section id="home">
            <h2>Featured Watches</h2>
            <div class="product-grid">
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=Analog+Watch" alt="Classic Analog Watch">
                    <h3>Classic Analog Watch</h3>
                    <p>$200.00</p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=Digital+Watch" alt="Digital Sports Watch">
                    <h3>Digital Sports Watch</h3>
                    <p>$150.00</p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=Smart+Watch" alt="Smart Fitness Watch">
                    <h3>Smart Fitness Watch</h3>
                    <p>$250.00</p>
                </div>
                <div class="product">
                    <img src="https://via.placeholder.com/250x200?text=Luxury+Watch" alt="Luxury Gold Watch">
                    <h3>Luxury Gold Watch</h3>
                    <p>$500.00</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 Timeless Watches. All rights reserved.</p>
    </footer>
</body>
</html>
