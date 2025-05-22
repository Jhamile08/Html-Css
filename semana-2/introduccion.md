# Introducción a CSS

## Breve repaso de HTML:

La semana pasada aprendimos HTML (HyperText Markup Language), que usamos para crear la estructura de una página web.
Con HTML podemos agregar:

    Títulos (<h1>)

    Párrafos (<p>)

    Imágenes (<img>)

    Listas (<ul>, <ol>)

    Enlaces (<a>)

    Tablas (<table>), entre otros elementos.

Pero hasta ahora, nuestra página no tenía colores, ni márgenes, ni tipografía atractiva...

## ¿Qué es CSS?

CSS significa "Cascading Style Sheets" o en español: Hojas de Estilo en Cascada.

Se utiliza para dar estilo a nuestro HTML, es decir, cambiar cómo se ven las cosas en nuestra página.

Con CSS podemos:

    Cambiar colores y fuentes

    Agregar bordes, márgenes y espaciado

    Hacer que un sitio sea responsive (adaptable)

    Animar elementos, etc.

## ¿Cómo aplicamos CSS?

### 1. Estilos internos usando la etiqueta <style>:

Podemos escribir CSS dentro de nuestro archivo HTML, en la sección <head>.
Así se ve:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi página con estilo</title>

  <!-- CSS interno -->
  <style>
    h1 {
      color: blue; /* Cambia el color del título a azul */
      font-family: Arial;
      text-align: center;
    }

    p {
      color: gray;
      font-size: 18px;
    }
  </style>
</head>
<body>
  <h1>Bienvenidos a mi sitio</h1>
  <p>Esto es un párrafo con estilo.</p>
</body>
</html>
```

### 2. Estilos externos con un archivo .css

Una mejor práctica es separar el CSS del HTML, escribiendo los estilos en un archivo aparte llamado style.css.

### style.css

```css
h1 {
  color: green;
  text-transform: uppercase;
}

p {
  font-style: italic;
  color: darkslategray;
}
```

### index.html

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Mi sitio separado</title>

  <!-- Vinculamos el archivo CSS externo -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Mi portafolio</h1>
  <p>Este es un ejemplo usando una hoja de estilo externa.</p>
</body>
</html>
```
La etiqueta <link> se coloca en el head y le dice al navegador que traiga los estilos desde el archivo style.css.

### ¿Por qué usar CSS externo?

- Mantiene el código limpio y ordenado

- Permite reutilizar estilos en varias páginas

- Es más fácil de mantener

# Formas de llamar a las etiquetas en CSS

Podés aplicar estilos a los elementos de tres formas:
### 1. Por nombre de etiqueta

Afecta a todas las etiquetas del mismo tipo.

```css
p {
  color: red;
}
```
## 2. Por clase (class)

Usá . seguido del nombre de la clase.
Afecta a los elementos que tengan ese atributo class.
```html
<p class="mensaje">Hola</p>

```
```css
.mensaje {
  font-size: 20px;
}

```
## 3. Por id (id)

Usá # seguido del nombre del id.
Debe ser único por página.
```html
<p id="importante">¡Atención!</p>
```
```css
#importante {
  color: blue;
}
```
### 4. Con selectores combinados

Podés combinar selectores para ser más específico.
```html
div p {
  color: green;
} /* Todos los <p> dentro de un <div> */
```
```css
.container .titulo {
  text-align: center;
}
```

# Entendiendo los espacios en CSS: el modelo de caja (Box Model)

En CSS, cada elemento HTML se comporta como una "caja", y esa caja tiene 4 partes fundamentales:
## 🔹 1. content (contenido)

Es el contenido real de la etiqueta (como un texto, imagen, etc.).
Ejemplo: si tenés un <p>Hola</p>, el texto "Hola" es el contenido.
## 🔹 2. padding (relleno)

Es el espacio entre el contenido y el borde de la caja.
Sirve para que el contenido no esté pegado al borde.
```css
p {
  padding: 10px; /* Espacio interior */
}
```

## 🔹 3. border (borde)

Es el borde de la caja. Puede tener grosor, color y estilo.
```css
p {
  border: 2px solid black; /* Borde negro, sólido, de 2px */
}
```

## 🔹 4. margin (margen)

Es el espacio por fuera del borde, que separa una caja de otra.
```css
p {
  margin: 20px; /* Espacio exterior */
}
```
## 🔹 En conclusión:
El margin aleja los elementos y el padding lo rellena

 Importante:
La combinación de estas 4 partes se conoce como el Modelo de Caja (Box Model). Podés ver una visualización aquí:
🔗 https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model