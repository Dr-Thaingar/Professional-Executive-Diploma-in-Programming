# Professional-Executive-Diploma-in-Programming
Borcelle Fresh Cooking website by using HTML (academic purpose)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Borcelle Fresh Cooking</title>
    <style>
        body {
            font-family: 'Times New Roman', Times, serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #001f3f;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #001f3f;
        }
        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            background-color: #005f9f;
        }
        .container {
            padding: 20px;
        }
        h2 {
            color: #001f3f;
        }
        .photos img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
        }
        .prices ul {
            list-style-type: none;
            padding: 0;
        }
        .prices li {
            background-color: #e6e6e6;
            margin: 5px 0;
            padding: 10px;
        }
        .contact-form {
            background-color: #e6e6e6;
            padding: 20px;
            border-radius: 5px;
        }
        .contact-form label {
            display: block;
            margin-bottom: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #001f3f;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #005f9f;
        }
        footer {
            background-color: #001f3f;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Borcelle Fresh Cooking</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#photos">Cooking Photos</a>
    <a href="#prices">Prices</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container" id="about">
    <h2>About</h2>
    <p>Welcome to Borcelle Fresh Cooking! We are passionate about bringing the freshest ingredients to your kitchen, providing you with delicious and healthy meal options. Our team of expert chefs is dedicated to creating recipes that are both tasty and nutritious.</p>
</div>

<div class="container" id="photos">
    <h2>Cooking Photos</h2>
    <div class="photos">
        <img src="photo1.jpg" alt="Cooking Photo 1">
        <img src="photo2.jpg" alt="Cooking Photo 2">
        <img src="photo3.jpg" alt="Cooking Photo 3">
    </div>
</div>

<div class="container" id="prices">
    <h2>Prices</h2>
    <div class="prices">
        <ul>
            <li>Basic Cooking Class: $50</li>
            <li>Advanced Cooking Class: $100</li>
            <li>Gourmet Cooking Class: $150</li>
        </ul>
    </div>
</div>

<div class="container" id="contact">
    <h2>Contact</h2>
    <div class="contact-form">
        <form action="#" method="post">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </div>
</div>

<footer>
    <p>&copy; 2024 Borcelle Fresh Cooking. All rights reserved.</p>
</footer>

</body>
</html>
