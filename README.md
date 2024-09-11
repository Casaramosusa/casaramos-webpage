# casaramos-webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casa Ramos - Vibrant Products</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff6f61;
            padding: 20px;
            text-align: center;
            color: #fff;
        }
        header h1 {
            margin: 0;
            font-size: 3em;
        }
        nav {
            background-color: #ff6f61;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        .banner {
            background-image: url('your-banner-image.jpg');
            background-size: cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
        }
        .banner h2 {
            font-size: 3em;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        section h2 {
            color: #ff6f61;
        }
        .products {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .product {
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            width: 30%;
            margin: 10px;
            padding: 20px;
            border-radius: 10px;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .product h3 {
            color: #333;
        }
        .cta {
            background-color: #ff6f61;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .cta a {
            background-color: white;
            color: #ff6f61;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 30px;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>Casa Ramos</h1>
        <p>Your trusted supplier for authentic Mexican flavors!</p>
    </header>

    <nav>
        <a href="#chiles">Dried Chiles</a>
        <a href="#aguas">Aguas Frescas</a>
        <a href="#spices">Spices</a>
        <a href="#snacks">Snacks</a>
        <a href="#contact">Contact Us</a>
    </nav>

    <div class="banner">
        <h2>Bringing You the Best of Mexican Flavors!</h2>
    </div>

    <section id="chiles">
        <h2>Dried Chiles</h2>
        <div class="products">
            <div class="product">
                <img src="chile-image-1.jpg" alt="Dried Chiles">
                <h3>Chile de Árbol</h3>
                <p>Spicy and vibrant, perfect for salsas and sauces.</p>
            </div>
            <div class="product">
                <img src="chile-image-2.jpg" alt="Dried Chiles">
                <h3>Guajillo Chiles</h3>
                <p>Mild heat and fruity flavor, ideal for moles and marinades.</p>
            </div>
        </div>
    </section>

    <section id="aguas">
        <h2>Aguas Frescas</h2>
        <div class="products">
            <div class="product">
                <img src="aguas-image-1.jpg" alt="Aguas Frescas">
                <h3>Horchata</h3>
                <p>A refreshing and creamy rice-based drink with cinnamon flavor.</p>
            </div>
            <div class="product">
                <img src="aguas-image-2.jpg" alt="Aguas Frescas">
                <h3>Tamarindo</h3>
                <p>Sweet and tangy, made from tamarind pulp.</p>
            </div>
        </div>
    </section>

    <section id="spices">
        <h2>Spices</h2>
        <div class="products">
            <div class="product">
                <img src="spice-image-1.jpg" alt="Spices">
                <h3>Cumin</h3>
                <p>A staple in Mexican cuisine, adding warmth and depth to dishes.</p>
            </div>
            <div class="product">
                <img src="spice-image-2.jpg" alt="Spices">
                <h3>Paprika</h3>
                <p>Rich, smoky, and a must-have for many traditional recipes.</p>
            </div>
        </div>
    </section>

    <section id="snacks">
        <h2>Snacks & Toppings</h2>
        <div class="products">
            <div class="product">
                <img src="snack-image-1.jpg" alt="Snacks">
                <h3>Takis Chips</h3>
                <p>Crunchy, spicy, and addictive. The ultimate snack!</p>
            </div>
            <div class="product">
                <img src="snack-image-2.jpg" alt="Snacks">
                <h3>Sweet Topping Candy Gummies</h3>
                <p>Delicious gummies covered in a sweet and tangy topping.</p>
            </div>
        </div>
    </section>

    <div class="cta" id="contact">
        <h2>Interested in Our Products?</h2>
        <p>Contact us today to place your order or to inquire about our wide variety of authentic Mexican products!</p>
        <a href="mailto:casaramosusa@gmail.com">Order Now</a>
    </div>

    <footer>
        <p>Casa Ramos - Milwaukee, WI | Contact: 414-888-0746 | 414-828-8622</p>
        <p>Email: casaramosusa@gmail.com</p>
    </footer>

</body>
</html>
