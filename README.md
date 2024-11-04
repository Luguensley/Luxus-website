<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxus - Boutique de vêtements de luxe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <h1>Luxus</h1>
            <nav>
                <ul>
                    <li><a href="#home">Accueil</a></li>
                    <li><a href="#products">Produits</a></li>
                    <li><a href="#about">À propos</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <button class="btn-cart">Panier</button>
        </div>
    </header>

    <!-- Section d'accueil -->
    <section id="home" class="home-banner">
        <div class="home-content">
            <h2>Découvrez le Luxe Ultime</h2>
            <p>Des collections exclusives de vêtements de créateurs, à portée de clic.</p>
            <button class="btn-shop">Explorez la Collection</button>
        </div>
    </section>

    <!-- Section Produits -->
    <section id="products">
        <h2>Nos Produits</h2>
        <div class="product-grid">
            <!-- Produit 1 : Robe de soirée -->
            <div class="product">
                <img src="path_to_image_of_evening_dress.jpg" alt="Robe de soirée élégante">
                <h3>Robe de Soirée Élégante</h3>
                <p>€499,99</p>
            </div>
            <!-- Ajoutez d'autres produits ici avec des images générées pour des costumes de luxe, accessoires, etc. -->
        </div>
    </section>

    <!-- Section À propos -->
    <section id="about">
        <h2>À propos de Luxus</h2>
        <p>Luxus est votre destination pour des vêtements de luxe, alliant qualité, élégance et style unique.</p>
    </section>

    <!-- Section Contact -->
    <section id="contact">
        <h2>Contactez-nous</h2>
        <form>
            <input type="text" name="name" placeholder="Nom">
            <input type="email" name="email" placeholder="Email">
            <textarea name="message" placeholder="Votre message"></textarea>
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Luxus. Tous droits réservés.</p>
    </footer>
</body>
</html>
/* styles.css */

body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #f5f5f5;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: white;
    padding: 10px 20px;
}

header h1 {
    font-family: 'Garamond', serif;
    font-size: 24px;
    color: gold;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin-right: 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

.btn-cart, .btn-shop {
    background-color: gold;
    color: #333;
    border: none;
    padding: 10px 15px;
    cursor: pointer;
}

.home-banner {
    background-image: url('https://files.oaiusercontent.com/file-DuWYXvCBmfkShvripJufFOlQ?se=2024-11-04T06%3A55%3A33Z&sp=r&sv=2024-08-04&sr=b&rscc=max-age%3D604800%2C%20immutable%2C%20private&rscd=attachment%3B%20filename%3De9355216-8082-4714-ab98-ce027d303454.webp&sig=TEcdNQwWZuVWIz3dgee5NzWzLCmhcTyU7Q9W6cvOanE%3D');
    background-size: cover;
    background-position: center;
    padding: 100px 20px;
    text-align: center;
    color: white;
}

.home-content h2 {
    font-size: 36px;
    margin-bottom: 20px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    padding: 20px;
}

.product img {
    width: 100%;
    border-radius: 10px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px;
    font-size: 14px;
}

