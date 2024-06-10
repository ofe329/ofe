<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tienda de Pasteles Online</title>
  <link rel="stylesheet" href="pasteles.css">
</head>
<body>
  <header>
    <h1>Tienda de Pasteles </h1>
  </header>

  <section class="catalogo">
    <h2>Selecciona tu pastel</h2>
    <div class="pastel">
      <img src="pastel.jpg" alt="Pastel de Chocolate">
      <h3>Pastel de Chocolate</h3>
      <p>Precio: $20.00</p>
      <button onclick="agregarAlCarrito('Pastel de Chocolate')">Agregar al carrito</button>
    </div>
    <div class="pastel">
      <img src="fresa.jpg" alt="Pastel de Fresa">
      <h3>Pastel de Fresa</h3>
      <p>Precio: $22.00</p>
      <button onclick="agregarAlCarrito('Pastel de Fresa')">Agregar al carrito</button>
    </div>

    <div class="pastel">
      <img src="vainilla.jpg" alt="Pastel de Vainilla">
      <h3>Pastel de Vainilla</h3>
      <p>Precio: $18.00</p>
      <button onclick="agregarAlCarrito('Pastel de Vainilla')">Agregar al carrito</button>
    </div>

    <div class="pastel">
      <img src="zanahoria.jpg" alt="Pastel de Zanahoria">
      <h3>Pastel de Zanahoria</h3>
      <p>Precio: $19.00</p>
      <button onclick="agregarAlCarrito('Pastel de Zanahoria')">Agregar al carrito</button>
    </div>
    <div class="pastel">
      <img src="limon.jpg" alt="Pastel de limon">
      <h3>Pastel de Limon</h3>
      <p>Precio: $15.00</p>
      <button onclick="agregarAlCarrito('Pastel de limon')">Agregar al carrito</button>
    </div>
    <div class="pastel">
      <img src="nuez.jpg" alt="Pastel de nuez">
      <h3>Pastel de Nuez</h3>
      <p>Precio: $25.00</p>
      <button onclick="agregarAlCarrito('Pastel de nuez')">Agregar al carrito</button>
    </div>
  </section>

  <footer>
   
  </footer>

  <script>
    function agregarAlCarrito(nombrePastel) {
   
      let formaPago = prompt("Por favor, elige tu forma de pago (Efectivo, Tarjeta):");
      alert("¡Feliz día! Has agregado el pastel '" + nombrePastel + "' al carrito. Forma de pago: " + formaPago);
    }
  </script>
</body>
</html>
