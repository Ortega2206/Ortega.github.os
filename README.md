<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>69 Hats - Tienda de Gorras</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <audio autoplay loop>
        <source src="audio.mp3" type="audio/mpeg">
        Tu navegador no soporta audio.
    </audio>

    <header>
        <h1>🧢 69 Hats</h1>
        <div id="cart-icon">🛒 <span id="cart-count">0</span></div>
    </header>

    <marquee class="welcome">🔥 Bienvenido a 69 Hats, la mejor tienda de gorras con estilo exclusivo 🔥</marquee>

    <section id="products">
        <div class="product">
            <img src="img/gorra1.jpg" alt="Gorra Negra">
            <h2>Gorra Negra</h2>
            <p>$20.00</p>
            <button onclick="addToCart('Gorra Negra', 20)">Agregar al carrito</button>
        </div>

        <div class="product">
            <img src="img/gorra2.jpg" alt="Gorra Roja">
            <h2>Gorra Roja</h2>
            <p>$25.00</p>
            <button onclick="addToCart('Gorra Roja', 25)">Agregar al carrito</button>
        </div>

        <div class="product">
            <img src="img/gorra3.jpg" alt="Gorra Azul">
            <h2>Gorra Azul</h2>
            <p>$22.00</p>
            <button onclick="addToCart('Gorra Azul', 22)">Agregar al carrito</button>
        </div>
    </section>

    <section id="checkout">
        <h2>Finalizar Compra</h2>
        <form id="payment-form">
            <input type="text" placeholder="Nombre" required>
            <input type="text" placeholder="Apellido" required>
            <input type="text" placeholder="Dirección" required>
            <input type="tel" placeholder="Teléfono" required>
            <input type="number" placeholder="Número de Tarjeta" required>
            <button type="submit">Pagar</button>
        </form>
    </section>

    <footer>
        <p>© 2025 69 Hats | Todos los derechos reservados</p>
    </footer>

</body>
</html>
