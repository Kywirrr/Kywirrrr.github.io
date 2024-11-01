<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Online Vintage Racing Jackets</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Raleway:wght@400&display=swap" rel="stylesheet">
    <style>
        /* Global Styling */
        body {
            font-family: 'Raleway', sans-serif;
            background-color: #f7f3e9;
            margin: 0;
            padding: 0;
            color: #4e4e4e;
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5rem;
        }

        h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2rem;
        }

        p {
            text-align: center;
        }
        
        /* Header Styling */
        .header {
            background-color: #b1a7a6;
            color: #ffffff;
            padding: 1.5rem;
            text-align: center;
        }

        /* Navigation Styling */
        .navbar {
            display: flex;
            justify-content: center;
            background-color: #d9cfc1;
            padding: 1rem;
        }

        .navbar a {
            color: #4e4e4e;
            text-decoration: none;
            padding: 0.5rem 1.5rem;
            margin: 0 0.5rem;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .navbar a:hover {
            background-color: #c4b8ab;
        }

        /* Section Styling */
        .section {
            padding: 2rem;
            text-align: center;
        }

        /* Home Section */
        #home {
            background-color: #f0e5cf;
            color: #4e4e4e;
        }

        /* About Section */
        #about {
            background-color: #e2dad4;
            color: #4e4e4e;
        }

        /* Product Section Styling */
        #products {
            background-color: #f6f1eb;
            color: #4e4e4e;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 1rem;
        }

        .product-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 1rem;
            width: 250px;
            padding: 1rem;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .product-card img {
            max-width: 100%;
            border-radius: 8px;
        }

        .buy-btn {
            background-color: #8c7c70;
            color: white;
            padding: 0.5rem 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .buy-btn:hover {
            background-color: #bfa899;
        }

        /* Contact Section */
        #contact {
            background-color: #dfcdc3;
            color: #4e4e4e;
        }

        /* Footer Styling */
        .footer {
            background-color: #b1a7a6;
            color: white;
            padding: 1rem;
            text-align: center;
            margin-top: 1.5rem;
        }

        /* Simple Animation */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .product-card {
            animation: fadeIn 1s ease-in;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <div class="header">
        <h1>Vintage Racing Jackets Store</h1>
        <p>Dapatkan Jaket Balap Vintage Terbaik di Sini!</p>
    </div>

    <!-- Navigation Bar -->
    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </div>

    <!-- Home Section -->
    <section id="home" class="section">
        <h2>Selamat Datang di Vintage Racing Jackets Store</h2>
        <p>Temukan koleksi jaket balap vintage eksklusif yang hanya ada di sini!</p>
    </section>

    <!-- About Section -->
    <section id="about" class="section">
        <h2>About Us</h2>
        <p>Vintage Racing Jackets Store adalah toko online yang menyediakan jaket balap vintage berkualitas tinggi. Kami percaya bahwa gaya klasik tidak akan pernah ketinggalan zaman.</p>
    </section>

    <!-- Products Section -->
    <section id="products" class="section">
        <h2>Our Products</h2>
        <div class="products">
            <div class="product-card">
                <img src="ClipDown.App_463436349_17897425971080033_537504320365675814_n.jpg" alt="Jaket Vintage 1">
                <h2>Jaket Vintage 1</h2>
                <p>Rp 350.000</p>
                <button class="buy-btn">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="ClipDown.App_461825329_17895269595080033_8974472220173998544_n.jpg" alt="Jaket Vintage 2">
                <h2>Jaket Vintage 2</h2>
                <p>Rp 400.000</p>
                <button class="buy-btn">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="ClipDown.App_457395480_17890767546080033_3391852893538391502_n.jpg" alt="Jaket Vintage 3">
                <h2>Jaket Vintage 3</h2>
                <p>Rp 450.000</p>
                <button class="buy-btn">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="photo.jpeg" alt="Jaket Vintage 4">
                <h2>Jaket Vintage 4</h2>
                <p>Rp 500.000</p>
                <button class="buy-btn">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="photo 2.jpeg" alt="Jaket Vintage 5">
                <h2>Jaket Vintage 5</h2>
                <p>Rp 550.000</p>
                <button class="buy-btn">Beli Sekarang</button>
            </div>
            <div class="product-card">
                <img src="photo 3.jpeg" alt="Jaket Vintage 6">
                <h2>Jaket Vintage 6</h2>
                <p>Rp 600.000</p>
                <button class="buy-btn">Beli Sekarang</button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Jika ada pertanyaan atau ingin bertanya tentang produk kami, silakan hubungi kami:</p>
        <p>Email: support@vintagejackets.com</p>
        <p>Telepon: +62 813-1714-9440</p>
    </section>

    <!-- Footer -->
    <div class="footer">
        <p>&copy; 2024 Vintage Racing Jackets Store</p>
    </div>
</body>
</html>
