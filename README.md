<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Billa Real Estate</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav {
            background-color: #444;
            padding: 10px 0;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 5px;
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .content {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #101010;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            height: 3%;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.1);
        }
        .property {
            border: 1px solid #ccc;
            margin-bottom: 20px;
            border-radius: 5px;
            overflow: hidden;
        }
        .property img {
            width: 100%;
            height: auto;
        }
        .property-info {
            padding: 10px;
        }
        .property-info h3 {
            margin-top: 0;
        }
        .property-info p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Billa Real Estate</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">Properties</a>
        <a href="#">About Us</a>
        <a href="#">Contact</a>
    </nav>
    <div class="container">
        <div class="content">
            <h2>Featured Properties</h2>
            <div class="property">
                <img src="10.jpg" alt="Property Image">
                <div class="property-info">
                    <h3>Beautiful Villa in subedari</h3>
                    <p>Location: subedari hanamakonda</p>
                    <p>Price: 20,00,000</p>
                </div>
            </div>
            <div class="property">
                <img src="20.jfif" alt="Property Image">
                <div class="property-info">
                    <h3>Luxury Apartment in Kazipet</h3>
                    <p>Location: Kazipet</p>
                    <p>Price: 30,00,000</p>
                </div>
            </div>
            <div class="property">
                <img src="30.jfif" alt="Property Image">
                <div class="property-info">
                    <h3>Spacious Family Home</h3>
                    <p>Location: warangal</p>
                    <p>Price: 25,00,000</p>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Billa Real Estate. All rights reserved.</p>
    </footer>
</body>
</html>
