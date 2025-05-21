# HTML: Lenguaje de etiquetas de hipertextoHTML: Lenguaje de etiquetas de hipertexto

##  ¿Qué es HTML?

**HTML** (Lenguaje de Marcas de Hipertexto, del inglés *HyperText Markup Language*) es el lenguaje fundamental de la Web. Se utiliza para definir la **estructura** y el **significado del contenido** en una página web.

###  ¿Qué significa "Hipertexto"?

"Hipertexto" se refiere a los **enlaces** que conectan páginas web entre sí, tanto dentro de un mismo sitio como entre sitios distintos. Estos enlaces son la base de la **World Wide Web**.

###  ¿Cómo funciona?

HTML utiliza **"marcas" o "etiquetas"** para identificar y organizar el contenido (texto, imágenes, multimedia, etc.) dentro de un navegador web. Estas etiquetas forman los **elementos HTML**, y su sintaxis básica es:

```html
<nombre-del-elemento>Contenido</nombre-del-elemento>
```

Por ejemplo: <p>Hola mundo</p>
 Ejemplos de etiquetas HTML comunes:
```html
    <head>, <title>, <body>

    <header>, <footer>, <article>, <section>

    <p>, <div>, <span>

    <img>, <video>, <audio>

    <ul>, <ol>, <li>

    <nav>, <aside>, <canvas>, <embed>
```    
    entre otras.

## Notas adicionales:

    Las etiquetas no distinguen entre mayúsculas y minúsculas: <title>, <Title>, y <TITLE> son válidas (aunque lo recomendado es usar minúsculas por buenas prácticas).

    HTML suele combinarse con CSS para el diseño y con JavaScript para la funcionalidad.

## ¿Qué es HTML semántico?

El **HTML semántico** utiliza etiquetas que tienen un **significado claro** sobre el contenido que contienen. Estas etiquetas ayudan a que **navegadores**, **motores de búsqueda** y **tecnologías de asistencia** (como lectores de pantalla) comprendan mejor la estructura y el propósito del contenido.

### 🔹 Ejemplos de etiquetas semánticas:

- `<header>`: encabezado de una página o sección.  
- `<nav>`: contiene enlaces de navegación.  
- `<main>`: contenido principal del documento.  
- `<section>`: agrupa contenido relacionado.  
- `<article>`: contenido independiente (como un post).  
- `<footer>`: pie de página.  
- `<aside>`: contenido complementario.  

###  ¿Por qué es importante?

- Mejora la **accesibilidad**.  
- Facilita el **SEO** (posicionamiento en buscadores).  
- Hace que el código sea más **fácil de leer y mantener**.  

---

##  ¿Qué es HTML no semántico?

El **HTML no semántico** usa etiquetas **genéricas** que no indican claramente su propósito. Estas etiquetas funcionan, pero **no transmiten información** sobre el contenido.

### 🔹 Ejemplos de etiquetas no semánticas:

- `<div>`: contenedor genérico.  
- `<span>`: contenedor en línea sin significado específico.  

Estas etiquetas son útiles para diseño y estructura, pero no aportan significado por sí solas.
