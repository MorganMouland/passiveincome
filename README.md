<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gut Go Drops</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #009688;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        h1 {
            font-size: 28px;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            background-color: #333;
            overflow: hidden;
        }

        nav li {
            float: left;
        }

        nav li a {
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        nav li a:hover {
            background-color: #4CAF50;
        }

        section {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        h2 {
            color: #333;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 20px;
        }

        a {
            text-decoration: none;
            color: #009688;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            background-color: #009688;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Gut Go Drops</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#products">Products</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>About Us</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
    </section>

    <section id="products">
        <h2>Our Products</h2>
        <p>Explore our range of Gut Go Drops products:</p>
        <ul>
            <li>
                <h3>Product 1</h3>
                <p>Description of Product 1. <a href="product_1">Learn More</a></p>
            </li>
            <li>
                <h3>Product 2</h3>
                <p>Description of Product 2. <a href="product_2">Learn More</a></p>
            </li>
            <!-- Add more products as needed -->
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>If you have any questions or inquiries, please contact us:</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea><br>

            <input type="submit" value="Submit">
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Gut Go Drops</p>
    </footer>
</body>
</html>
