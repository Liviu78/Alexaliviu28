
<!DOCTYPE html>
<html>
<head>
    <title>Alexaliviu28.ro - Produse</title>
    <style>
        /* Stiluri globale */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Stiluri pentru antet */
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        /* Stiluri pentru produse */
        .product-list {
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            background-color: #f5f5f5;
        }

        .product-item {
            margin-bottom: 20px;
            padding: 10px;
            background-color: #fff;
            border: 1px solid #ccc;
        }

        .product-item h2 {
            margin-top: 0;
        }

        .product-item p {
            margin-bottom: 5px;
        }

        .product-image {
            width: 200px;
            height: auto;
            margin-bottom: 10px;
        }

        .add-to-cart {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #333;
            color: #fff;
            border: none;
        }

        .add-to-cart:hover {
            background-color: #555;
        }

        /* Stiluri pentru subsol */
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
        <h1>Alexaliviu28.ro</h1>
        <nav>
            <ul>
                <li><a href="index.html">Acasă</a></li>
                <li><a href="produse.html">Produse</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="product-list">
            <div class="product-item">
                <img class="product-image" src="/storage/emulated/0/Download/iphone.jpg" alt="iPhone 13">
                <h2>iPhone 13</h2>
                <p>Preț: $1.299</p>
                <button class="add-to-cart">Adaugă în coș</button>
            </div>
            <div class="product-item">
                <img class="product-image" src="/storage/emulated/0/Download/samsung.jpg" alt="Samsung Galaxy S21">
                <h2>Samsung Galaxy S21</h2>
                <p>Preț: $999</p>
                <button class="add-to-cart">Adaugă în coș</button>
            </div>
            <div class="product-item">
                <img class="product-image" src="/storage/emulated/0/Download/pixel.jpg" alt="Google Pixel 6">
                <h2>Google Pixel 6</h2>
                <p>Preț: $799</p>
                <button class="add-to-cart">Adaugă în coș</button>
            </div>
        </div>
    </main>

    <footer>
        <p>&copy; 2023 Alexaliviu28.ro. Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
