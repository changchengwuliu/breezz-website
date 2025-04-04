# breezz-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Breezz - Eco-Friendly Toilet Paper</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" href="Favicon Original.ico" type="image/x-icon">
</head>
<body>
    <header>
        <nav>
            <div class="logo">
                <img src="Favicon Original.ico" alt="Breezz Logo">
                <h1>Breezz</h1>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#cart">Cart</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="home">
        <div class="hero">
            <h2>Soft as clouds, Strong as Pines</h2>
            <p>The Breezz Standard - Eco-friendly, soft, and strong toilet paper.</p>
            <img src="1.png" alt="Breezz Toilet Paper">
        </div>
    </section>
    
    <section id="about">
        <h2>Our Eco-Friendly Mission</h2>
        <p>Breezz is committed to sustainability. Our toilet paper is made from responsibly sourced materials, reducing environmental impact while providing premium comfort and strength.</p>
    </section>
    
    <section id="products">
        <h2>Our Products</h2>
        <div class="product">
            <img src="2.png" alt="Breezz Packaging">
            <p>Breezz Super Soft Toilet Paper - 9 Rolls, 3 Ply, 160 Sheets per Roll.</p>
            <p>Price: $6.99 per pack</p>
            <label for="quantity">Choose quantity:</label>
            <select id="quantity">
                <option value="1">Single Pack - $6.99</option>
                <option value="3">Pack of 3 - $19.99</option>
                <option value="6">Pack of 6 - $37.99</option>
                <option value="12">Pack of 12 - $69.99</option>
            </select>
            <button onclick="addToCart()">Add to Cart</button>
        </div>
        
        <div class="subscription">
            <h3>Subscribe & Save</h3>
            <p>Get Breezz toilet paper delivered to your door every month at a discounted price.</p>
            <label for="subscription">Choose Subscription Plan:</label>
            <select id="subscription">
                <option value="monthly">Monthly Delivery - $6.49/pack</option>
                <option value="bi-monthly">Bi-Monthly Delivery - $6.29/pack</option>
                <option value="quarterly">Quarterly Delivery - $5.99/pack</option>
            </select>
            <button onclick="subscribeNow()">Subscribe Now</button>
        </div>
    </section>
    
    <section id="customer-reviews">
        <h2>Customer Reviews</h2>
        <p>"The softest and most eco-friendly toilet paper I've ever used! - Sarah L."</p>
        <p>"Great quality and love the subscription service. - Michael D."</p>
    </section>
    
    <section id="cart">
        <h2>Your Shopping Cart</h2>
        <p>Cart is empty</p>
        <button onclick="checkout()">Proceed to Checkout</button>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have questions? Reach out to us!</p>
    </section>
    
    <footer>
        <p>&copy; 2025 Breezz. All rights reserved.</p>
    </footer>

    <script>
        function addToCart() {
            alert('Item added to cart!');
        }
        function subscribeNow() {
            alert('Subscription activated!');
        }
        function checkout() {
            alert('Proceeding to checkout...');
        }
    </script>
</body>
</html>
