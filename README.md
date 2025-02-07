<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menú del Restaurante</title>
    <link rel="icon" href="https://via.placeholder.com/150" type="image/x-icon"> <!-- Icono del restaurante -->
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }

        header {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }

        .menu-container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
        }

        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 15px;
            border-bottom: 1px solid #ddd;
            background-color: #fff;
            margin-bottom: 10px;
            border-radius: 8px;
        }

        .menu-item h3 {
            margin: 0;
        }

        .menu-item p {
            color: #777;
        }

        .menu-item span {
            font-weight: bold;
            color: #333;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Menú del Restaurante</h1>
</header>

<div class="menu-container">
    <div class="menu-item">
        <div>
            <h3>Pizza Margarita</h3>
            <p>Una pizza clásica con salsa de tomate, mozzarella y albahaca fresca.</p>
        </div>
        <span>$8.99</span>
    </div>

    <div class="menu-item">
        <div>
            <h3>Hamburguesa Clásica</h3>
            <p>Hamburguesa de carne de res con queso cheddar, lechuga, tomate y cebolla.</p>
        </div>
        <span>$5.99</span>
    </div>

    <div class="menu-item">
        <div>
            <h3>Ensalada César</h3>
            <p>Lechuga romana, crutones, queso parmesano, y aderezo César.</p>
        </div>
        <span>$4.49</span>
    </div>

    <div class="menu-item">
        <div>
            <h3>Pasta Alfredo</h3>
            <p>Pasta con salsa cremosa de ajo, mantequilla y queso parmesano.</p>
        </div>
        <span>$10.99</span>
    </div>

    <div class="menu-item">
        <div>
            <h3>Agua Mineral</h3>
            <p>Refresca con nuestra agua mineral fresca y pura.</p>
        </div>
        <span>$1.50</span>
    </div>
</div>

<footer>
    <p>&copy; 2025 Restaurante XYZ | Todos los derechos reservados</p>
</footer>

</body>
</html>
