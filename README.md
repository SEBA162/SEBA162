<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda en Línea</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a Nuestra Tienda</h1>
        <nav>
            <ul>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#carrito">Carrito</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="productos">
            <h2>Catálogo de Productos</h2>
            <div class="producto">
                <h3>Producto 1</h3>
                <p>Descripción del producto 1.</p>
                <button>Añadir al Carrito</button>
            </div>
            <div class="producto">
                <h3>Producto 2</h3>
                <p>Descripción del producto 2.</p>
                <button>Añadir al Carrito</button>
            </div>
            <!-- Añadir más productos aquí -->
        </section>

        <section id="carrito">
            <h2>Carrito de Compras</h2>
            <p>Tu carrito está vacío.</p>
            <!-- Aquí se mostrarán los productos añadidos al carrito -->
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Tienda en Línea</p>
    </footer>
</body>
</html>
/* Archivo: styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 10px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    padding: 20px;
}

.producto {
    border: 1px solid #ddd;
    padding: 10px;
    margin-bottom: 10px;
    background-color: white;
}

.producto h3 {
    margin: 0 0 10px 0;
}

footer {
    text-align: center;
    padding: 10px 0;
    background-color: #333;
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
}
