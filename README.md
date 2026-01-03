<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Clone</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f3f3f3; }
        header { background-color: #131921; color: white; padding: 10px; display: flex; align-items: center; }
        .logo { font-size: 24px; font-weight: bold; margin-right: 20px; }
        .search { flex: 1; display: flex; }
        .search input { flex: 1; padding: 8px; }
        .search button { padding: 8px 12px; background-color: #febd69; border: none; }
        nav { margin-left: 20px; }
        nav a { color: white; margin: 0 10px; text-decoration: none; }
        .container { max-width: 1200px; margin: 20px auto; padding: 20px; background: white; }
        .products { display: grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap: 20px; }
        .product { border: 1px solid #ddd; padding: 10px; text-align: center; }
        .product img { max-width: 100%; height: 150px; }
        .product h3 { font-size: 16px; margin: 10px 0; }
        .product p { color: #b12704; font-weight: bold; }
        .product button { background-color: #f0c14b; border: none; padding: 8px; cursor: pointer; }
        footer { background-color: #131921; color: white; text-align: center; padding: 20px; margin-top: 20px; }
        footer a { color: #ddd; margin: 0 10px; text-decoration: none; }
    </style>
</head>
<body>
    <header>
        <div class="logo">Amazon</div>
        <div class="search">
            <input type="text" placeholder="Search for products...">
            <button>Search</button>
        </div>
        <nav>
            <a href="#">Hello, Sign in</a>
            <a href="#">Returns & Orders</a>
            <a href="#">Cart</a>
        </nav>
    </header>

    <div class="container">
        <h2>Today's Deals</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=Product+1" alt="Product 1">
                <h3>Wireless Headphones</h3>
                <p>$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=Product+2" alt="Product 2">
                <h3>Smartphone Case</h3>
                <p>$19.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=Product+3" alt="Product 3">
                <h3>Laptop Stand</h3>
                <p>$29.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/200x150?text=Product+4" alt="Product 4">
                <h3>Bluetooth Speaker</h3>
                <p>$39.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2023 Amazon Clone. All rights reserved.</p>
        <a href="#">Conditions of Use</a>
        <a href="#">Privacy Notice</a>
        <a href="#">Interest-Based Ads</a>
    </footer>
</body>
</html>