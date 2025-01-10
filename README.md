<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Morocco Tours</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f4a261;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #264653;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #2a9d8f;
        }
        .banner {
            background-image: url('https://via.placeholder.com/1920x500');
            background-size: cover;
            background-position: center;
            height: 500px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 2em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .section {
            padding: 40px;
            text-align: center;
        }
        .section h2 {
            margin-bottom: 20px;
        }
        .card {
            display: inline-block;
            margin: 20px;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .card img {
            width: 300px;
            height: 200px;
            object-fit: cover;
        }
        .card h3 {
            background-color: #2a9d8f;
            color: white;
            margin: 0;
            padding: 10px;
        }
        .card p {
            padding: 15px;
        }
        footer {
            background-color: #264653;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Explore Morocco</h1>
        <p>Your Gateway to Adventure and Culture</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#tours">Tours</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="banner">
        Discover the Magic of Morocco
    </div>

    <section id="tours" class="section">
        <h2>Our Popular Tours</h2>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Sahara Desert">
            <h3>Sahara Desert Adventure</h3>
            <p>Experience the golden dunes of the Sahara and a night under the stars.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Atlas Mountains">
            <h3>Atlas Mountains Trek</h3>
            <p>Hike through the breathtaking Atlas Mountains and visit Berber villages.</p>
        </div>
        <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Marrakech">
            <h3>Marrakech City Tour</h3>
            <p>Explore the vibrant markets, palaces, and gardens of Marrakech.</p>
        </div>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Morocco Tours is dedicated to providing unforgettable travel experiences. We offer personalized tours to help you explore the rich culture, stunning landscapes, and warm hospitality of Morocco.</p>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: info@moroccotours.com</p>
        <p>Phone: +212-123-456-789</p>
    </section>

    <footer>
        &copy; 2025 Morocco Tours. All rights reserved.
    </footer>
</body>
</html>
