# DIGIBHEM2
E-Commerce landing page
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> THe OG E-Commerce</title>
    <style>
        /* Basic Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #ffffff;
        }

        header {
            background-color: #000000;
            color: white;
            padding: 10px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav {
            display: flex;
            gap: 15px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background: #1a1a1a;
        }

        .hero h1 {
            margin: 0;
            font-size: 36px;
            color: #ff4444;
        }

        .hero p {
            margin: 20px 0;
            font-size: 18px;
        }

        .hero button {
            background-color: #ff4444;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }

        .hero button:hover {
            background-color: #e63939;
        }

        .product-showcase {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .product {
            border: 1px solid #333;
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
            padding: 10px;
            background-color: #1a1a1a;
        }

        .product img {
            max-width: 100%;
            height: auto;
        }

        .product h3 {
            margin: 10px 0;
            font-size: 20px;
        }

        .product p {
            font-size: 16px;
            color: #888;
        }

        .product button {
            background-color: #ff4444;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
        }

        .product button:hover {
            background-color: #e63939;
        }

        .signup {
            padding: 30px;
            text-align: center;
            background: #1a1a1a;
        }

        .signup h2 {
            font-size: 28px;
            margin: 0 0 20px;
        }

        .signup form {
            display: flex;
            flex-direction: column;
            gap: 10px;
            max-width: 400px;
            margin: 0 auto;
        }

        .signup input {
            padding: 10px;
            font-size: 16px;
            border: 1px solid #333;
            border-radius: 4px;
            background-color: #1a1a1a;
            color: white;
        }

        .signup button {
            padding: 10px;
            font-size: 18px;
            background-color: #ff4444;
            color: white;
            border: none;
            cursor: pointer;
        }

        .signup button:hover {
            background-color: #e63939;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #000000;
            color: white;
        }

        @media (max-width: 600px) {
            header {
                flex-direction: column;
                align-items: flex-start;
            }

            nav {
                flex-wrap: wrap;
            }
        }
    </style>
</head>

<body>
    <header>
        <div class="logo">Sigma Shadows</div>
        <nav>
            <a href="#">Home</a>
            <a href="#products">Products</a>
            <a href="#signup">Join Us</a>
        </nav>
    </header>

    <div class="hero">
        <h1>Welcome to the Dark Side</h1>
        <p>Uncover the eerie and unique items you've been searching for.</p>
        <button onclick="alert('Step into the Shadows')">Explore Now</button>
    </div>

    <section id="products" class="product-showcase">
        <div class="product">
            <img src=D:\/Candle.jpg alt="Skull Candle">
            <h3>Skull Candle</h3>
            <p>$15.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src=D:\/Journal.jpg alt="Lockable Journal">
            <h3>Lockable Journal</h3>
            <p>$12.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src=D:\/bb.jpg alt="Hidden Storage Book">
            <h3>Hidden Storage Book</h3>
            <p>$18.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src=D:\/Mask.jpg alt="LED Mask">
            <h3>LED Mask</h3>
            <p>$25.99</p>
            <button>Add to Cart</button>
        </div>
    </section>

    <section id="signup" class="signup">
        <h2>Join the Sigma Circle</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="password" placeholder="Create Password" required>
            <button type="submit">Sign Up</button>
        </form>
    </section>

    <footer>
        &copy; 2025 Sigma Shadows. All Rights Reserved.
    </footer>
</body>

</html>
