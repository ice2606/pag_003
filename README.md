
<html>
<head>
<style>
  .titulo-pagina {
    /* Dimensiones del cuadro */
    width: 80%;       /* Puedes cambiar este valor (ej. 500px, 90%) */
    height: 100px;    /* Puedes cambiar este valor (ej. auto, 150px) */
    /* Colores */
    background-color: #3498db; /* Cambia este código por el color que desees */
    color: white;              /* Color del texto */  
    /* Centrado y estilo */
    margin: 20px auto;
    text-align: center;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }
  .titulo-pagina h1 {
    margin: 0;
    font-size: 2em;
/* Estilos generales para pantallas grandes (por defecto) */
body {
  font-family: Arial, sans-serif;
  padding: 20px;
}
.contenedor {
  width: 960px; /* Ancho fijo para pantallas grandes */
  margin: auto;
}
/* Media Query para pantallas de hasta 768px (tabletas y móviles) */
@media (max-width: 768px) {
  .contenedor {
    width: 90%; /* Ancho flexible para pantallas más pequeñas */
  }
}
/* Media Query para pantallas de hasta 480px (móviles) */
@media (max-width: 480px) {
  h1 {
    font-size: 24px; /* Cambia el tamaño de la fuente para que se lea mejor */
  }
  .contenedor {
    padding: 10px;
  }
}
  }
</style>
</head>
<body>

  <div class="titulo-pagina">
    <h1>BIENVENIDOS </h1>
  </div>

</body>
</html>





























<head>
<style>
  .contenedor-texto {
    width: 60%; /* Define el ancho del contenedor */
    margin: 0 auto; /* Centra el contenedor horizontalmente */
    text-align: center; /* Centra el texto dentro del contenedor */
    padding: 20px; /* Agrega espacio interno */
    border: 1px solid #ccc; /* Agrega un borde para visualizarlo */
      color:#000000;
background-color:38F527 ;
  }
</style>
</head>
<body>

  <div class="contenedor-texto">
    
  </div>

</body>







<a href="https://ice2606.github.io/pagina-002/" class="boton-verde">
  <button>atras </button>
</a>

<style>
  .boton-verde {
    text-decoration: none; /* Elimina el subrayado del enlace */
  }

  .boton-verde button {
    background-color: #4CAF50; /* Color de fondo verde */
    color: white; /* Color de la letra blanco */
    border: none;
    padding: 15px 32px;
    text-align: center;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
    border-radius: 8px; /* Bordes redondeados */
  }

  .boton-verde button:hover {
    background-color: #45a049; /* Color verde más oscuro al pasar el ratón */
  }
</style>




<html>
<head>
<style>
  body {
    background-image: url('tenis.jpg'); /* Reemplaza con la ruta de tu imagen */
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
  }

  /* Opcional: Estilos para hacer el texto legible */
  h1, p {
    color: white;
    text-shadow: 2px 2px 4px #000000;
  }
</style>
</head>
<body>


</body>
</html>






<html>
<head>
<title>Catálogo</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f5;
    margin: 0;
    padding: 20px;
    display: flex;
    justify-content: center;
  }
  table {
    width: 100%;
    max-width: 900px;
    border-collapse: collapse;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    background-color: white;
    table-layout: fixed; /* Mantiene las columnas de igual ancho */
  }
 th, td {
    padding: 15px;
    text-align: center;
    border: 1px solid #ddd;
  }
  th {
    background-color: #3f51b5;
    color: white;
  }
  tr:nth-child(even) {
    background-color: #f9f9f9;
  }
  tr:hover {
    background-color: #f1f1f1;
  }
.producto-img {
    width: 100px;
    height: 100px;
    object-fit: cover;
    border-radius: 5px;
  }
  .whatsapp-link {
    display: inline-block;
    background-color: #25D366;
    color: white;
    padding: 10px 15px;
    text-decoration: none;
    border-radius: 50px;
    font-weight: bold;
    transition: background-color 0.3s ease;
  }
  .whatsapp-link:hover {
    background-color: #128C7E;
  }
.precio {
    font-weight: bold;
    color: #007bff;
  }
  .descripcion {
    font-size: 14px;
    color: #666;
  }
  /* Media query para pantallas más pequeñas */
  @media (max-width: 768px) {
    table, thead, tbody, th, td, tr {
      display: block;
      width: 100%;
    }
    th {
      display: none; /* Oculta los encabezados de la tabla en pantallas pequeñas */
    }
    td {
      border: none;
      border-bottom: 1px solid #ddd;
      text-align: left;
      padding-left: 50%;
      position: relative;
    }
    td:before {
      content: attr(data-label);
      position: absolute;
      top: 6px;
      left: 6px;
      width: 45%;
      padding-right: 10px;
      white-space: nowrap;
      font-weight: bold;
    }
    .producto-img {
      display: block;
      margin: 0 auto;
    }  }
</style>
</head>
<body>
<table>
  <thead>
    <tr>
      <th>Foto</th>
      <th>Descripción</th>
      <th>Precio</th>
      <th>Comprar</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-label="Foto"><img src="01.jpg" alt="Producto 1" class="producto-img"></td>
      <td data-label="Descripción"><span class="descripcion">sandalias con perlas hermosas talla del 35 al 40.</span></td>
      <td data-label="Precio"><span class="precio"></span></td>
      <td data-label="Comprar"><a href="https://wa.me/+505 8990 6649?text=Hola,%20me%20interesa%20el%20Producto%201%20de%20tu%20sitio%20web." class="whatsapp-link" target="_blank">WhatsApp</a></td>
    </tr>
    <tr>
      <td data-label="Foto"><img src="03.jpg " alt="Producto 2" class="producto-img"></td>
      <td data-label="Descripción"><span class="descripcion">sandalias color plateado con perlas tallas 35 al 40.</span></td>
      <td data-label="Precio"><span class="precio"></span></td>
      <td data-label="Comprar"><a href="https://wa.me/+505 8990 6649?text=Hola,%20me%20interesa%20el%20Producto%202%20de%20tu%20sitio%20web." class="whatsapp-link" target="_blank">WhatsApp</a></td>
    </tr>
    <tr>
      <td data-label="Foto"><img src="04.jpg" alt="Producto 3" class="producto-img"></td>
      <td data-label="Descripción"><span class="descripcion">sandalias color dorado con flores doradas </span></td>
      <td data-label="Precio"><span class="precio"></span></td>
      <td data-label="Comprar"><a href="https://wa.me/+505 8990 6649?text=Hola,%20me%20interesa%20el%20Producto%203%20de%20tu%20sitio%20web." class="whatsapp-link" target="_blank">WhatsApp</a></td>
    </tr>
  <tr>
      <td data-label="Foto"><img src="05.jpg" alt="Producto 1" class="producto-img"></td>
      <td data-label="Descripción"><span class="descripcion">sandalias color negro con flores negras del 35 al 40</span></td>
      <td data-label="Precio"><span class="precio"></span></td>
      <td data-label="Comprar"><a href="https://wa.me/+505 8990 6649?text=Hola,%20me%20interesa%20el%20Producto%201%20de%20tu%20sitio%20web." class="whatsapp-link" target="_blank">WhatsApp</a></td>
    </tr>
  <tr>
      <td data-label="Foto"><img src="06.jpg" alt="Producto 1" class="producto-img"></td>
      <td data-label="Descripción"><span class="descripcion">sandalias color gris con flores gris del 35 al 40 .</span></td>
      <td data-label="Precio"><span class="precio"></span></td>
      <td data-label="Comprar"><a href="https://wa.me/+505 8990 6649?text=Hola,%20me%20interesa%20el%20Producto%201%20de%20tu%20sitio%20web." class="whatsapp-link" target="_blank">WhatsApp</a></td>
    </tr>
    </tbody>
</table>
</body>
</html>



