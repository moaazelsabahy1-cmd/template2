# template2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Your Brand Name] - Premium Clothing</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #333; color: white; padding: 1rem; text-align: center; }
        nav { background-color: #222; padding: 0.5rem; }
        nav ul { list-style: none; padding: 0; margin: 0; display: flex; justify-content: center; }
        nav li { margin: 0 1rem; }
        nav a { color: white; text-decoration: none; }
        .hero { background-image: url('https://via.placeholder.com/1200x400?text=Hero+Banner'); background-size: cover; height: 400px; display: flex; align-items: center; justify-content: center; color: white; text-shadow: 2px 2px 4px rgba(0,0,0,0.5); }
        .products { padding: 2rem; text-align: center; }
        .product-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; }
        .product { background: white; padding: 1rem; border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        footer { background-color: #333; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
    </style>
</head>
<body>
    <header>
        <h1>[Your Brand Name]</h1>
        <p>Stylish, Sustainable Clothing for Everyone</p>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section class="hero">
        <h2>Welcome to [Your Brand Name]</h2>
        <p>Discover our latest collection of branded apparel.</p>
    </section>
    <section id="products" class="products">
        <h2>Featured Products</h2>
        <div class="product-grid">
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=T-Shirt" alt="Branded T-Shirt" style="width: 100%; border-radius: 8px;">
                <h3>Classic T-Shirt</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=Hoodie" alt="Branded Hoodie" style="width: 100%; border-radius: 8px;">
                <h3>Premium Hoodie</h3>
                <p>$59.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/250x250?text=Jacket" alt="Branded Jacket" style="width: 100%; border-radius: 8px;">
                <h3>Stylish Jacket</h3>
                <p>$89.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2023 [Your Brand Name]. All rights reserved.<p>
        <p>Follow us on social media for the latest updates.<p>
    </footer>
</body>
</html>
