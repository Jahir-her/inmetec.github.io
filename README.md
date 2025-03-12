<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inmetec - Soluciones HVAC</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            background-color: #0056b3;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 15px;
            font-size: 18px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .product, .contact {
            background: white;
            padding: 15px;
            margin: 15px;
            width: 300px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        button {
            padding: 10px;
            margin-top: 10px;
            font-size: 16px;
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #218838;
        }
        .contact p {
            font-size: 16px;
            margin: 5px 0;
        }
    </style>
</head>
<body>
    <header>Inmetec - Desarrollo y Ejecución de Sistemas de Climatización HVAC</header>
    <nav>
        <a href="#productos">Productos</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="container">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Producto 1">
                <h3>Producto 1</h3>
                <p>Descripción del producto 1.</p>
                <button>Ver más</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Producto 2">
                <h3>Producto 2</h3>
                <p>Descripción del producto 2.</p>
                <button>Ver más</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Producto 3">
                <h3>Producto 3</h3>
                <p>Descripción del producto 3.</p>
                <button>Ver más</button>
            </div>
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <div class="contact">
            <p><strong>Dirección:</strong> Calle Diego Ferre 507, Urb. Los Robles, Sta. Anita - Lima</p>
            <p><strong>Sitio Web:</strong> <a href="http://www.inmetec.com.pe" target="_blank">www.inmetec.com.pe</a></p>
            <p><strong>Correo:</strong> jherrera@inmetec.com.pe | ventas@inmetec.com.pe</p>
            <p><strong>Teléfonos:</strong> (+51) 017576199 / 926898942</p>
        </div>
    </section>
</body>
</html>
