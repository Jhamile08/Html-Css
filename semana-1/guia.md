<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Esta etiqueta define el tipo de documento: HTML5 -->
    <meta charset="UTF-8"> <!-- Permite mostrar caracteres especiales como ñ, tildes, símbolos -->
    
    <!-- Hace que la página se vea bien en dispositivos móviles (diseño responsive) -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Conecta una hoja de estilos externa (CSS) -->
    <link rel="stylesheet" href="./style.css">
    
    <!-- Define el título que aparece en la pestaña del navegador -->
    <title>Html</title>
</head>
<body>

    <!-- Encabezados: se usan para títulos. El h1 es el más importante y solo debe haber uno por página -->
    <h1 class="titulo">Andrea Dominguez</h1>
    <h2 class="titulo">Andrea Dominguez</h2>
    <h3 class="titulo">Andrea Dominguez</h3>
    <h4 class="titulo">Andrea Dominguez</h4>

    <!-- Contenedor principal con estilo en línea (uso de Flexbox para centrar contenido) -->
    <div class="container" style="display: flex; justify-content: center;">

        <!-- Contenedor para una descripción en párrafo -->
        <div>
            <!-- <p> se usa para escribir párrafos de texto -->
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aut minima illum minus, corrupti excepturi assumenda</p>
        </div>

        <!-- Imagen decorativa o representativa de la página -->
        <img src="./images/1400x846 HYDHYD 2.jpg" alt="Capibara" style="width: 100px; height: 100px;">

        <!-- <nav> se utiliza para la barra de navegación, con enlaces a secciones internas o externas -->
        <nav> 
            <!-- <b> sirve para resaltar el texto en negrita -->
            <h2><b>Desarrolladora web</b></h2> 

            <!-- Lista ordenada: los elementos se numeran automáticamente -->
            <ol>
                <li>Sobre mí</li>
                <li>Descripción</li>
                <li>Nosotros</li>
            </ol>
        </nav> 
    </div>

    <!-- <main> representa el contenido principal de la página -->
    <main>
        <h2>Bienvenidos</h2>
        <p>Esta es una página de prueba para aprender sobre etiquetas semánticas.</p>
        
        <!-- Contenedor para una imagen dentro del contenido principal -->
        <div>
            <img src="" alt="Imagen relacionada">
        </div>
    </main>

    <!-- <footer> representa el pie de página. Aquí va la información de contacto, derechos, enlaces, etc. -->
    <footer>
        <h2>Contacto</h2>
        <!-- Enlace externo a YouTube -->
        <a href="https://www.youtube.com/watch?v=UFpAwT6Gir4" target="_blank">Animales</a>

        <!-- Tabla para mostrar datos organizados en filas y columnas -->
        <table border="1">
            <tr>
                <!-- Encabezados de columna -->
                <th>Nombre</th>
                <th>Edad</th>
            </tr>
            <!-- Filas con datos -->
            <tr>
                <td>Andrea</td>
                <td>11</td>
            </tr>
            <tr>
                <td>Andrea</td>
                <td>11</td>
            </tr>
            <tr>
                <td>Andrea</td>
                <td>11</td>
            </tr>
            <tr>
                <td>Andrea</td>
                <td>11</td>
            </tr>
            <tr>
                <td>Andrea</td>
                <td>11</td>
            </tr>
        </table>
    </footer>
    
</body>
</html>
