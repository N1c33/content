<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistema de Gestión de Pedidos</title>
    <style>
        /* Estilos CSS aquí */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        section {
            margin: 20px;
        }
        .menu-item {
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px;
            background-color: #fff;
            display: inline-block;
            width: 200px;
        }
        #order-summary {
            border: 1px solid #ddd;
            padding: 10px;
            margin-top: 20px;
            background-color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sistema de Gestión de Pedidos</h1>
    </header>

    <section>
        <h2>Menú</h2>
        <div class="menu-item">
            <h3>Entradas</h3>
            <ul>
                <li>Plato 1 - $10.99</li>
                <li>Plato 2 - $8.99</li>
            </ul>
        </div>

        <div class="menu-item">
            <h3>Platos Principales</h3>
            <ul>
                <li>Plato 3 - $15.99</li>
                <li>Plato 4 - $12.99</li>
            </ul>
        </div>

        <!-- Otros elementos del menú -->
    </section>

    <section>
        <h2>Realizar Pedido</h2>
        <div id="order-summary">
            <h3>Resumen del Pedido</h3>
            <!-- Aquí se mostrará el resumen del pedido -->
        </div>
    </section>

    <section>
        <h2>Registro de Clientes</h2>
        <form id="customer-form">
            <!-- Formulario de registro de clientes -->
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="phone">Teléfono:</label>
            <input type="tel" id="phone" name="phone" required>

            <label for="address">Dirección:</label>
            <input type="text" id="address" name="address" required>

            <button type="submit">Registrar Cliente</button>
        </form>
    </section>

    <script>
        // Lógica JavaScript aquí
        // Por ejemplo, puedes usar JavaScript para manejar eventos de clic, actualizar el resumen del pedido, etc.
    </script>
</body>
</html>
