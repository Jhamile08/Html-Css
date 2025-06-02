# Introducción a CSS Grid

**CSS Grid** es una herramienta poderosa de CSS que nos permite crear **diseños web en forma de cuadrícula (grid)** de manera muy flexible. A diferencia de otros métodos como `float`, `flexbox` o `position`, **Grid está diseñado especialmente para organizar elementos en filas y columnas**, lo que lo hace ideal para construir estructuras completas de páginas web.

---

## ¿Qué es una grid?

Una **grid** es una especie de *"tabla invisible"* que nos ayuda a posicionar elementos dentro de un contenedor. Podemos decidir **cuántas filas y columnas** queremos, y luego **colocar los elementos exactamente donde queramos** dentro de esa cuadrícula.

---

## ¿Por qué usar CSS Grid?

✅ Permite **dividir una página en secciones** de manera ordenada.  
✅ Puedes **alinear elementos fácilmente** tanto en filas como en columnas.  
✅ Hace que el diseño sea **más limpio y fácil de mantener**.  
✅ Es **responsivo**, lo que significa que se adapta bien a distintos tamaños de pantalla.

## "Flexbox es para una dimensión, Grid es para dos."

Ejemplo básico:
```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-template-rows: auto;
  gap: 10px;
}
```
```html
<div class="container">
  <div>Elemento 1</div>
  <div>Elemento 2</div>
  <div>Elemento 3</div>
  <div>Elemento 4</div>
</div>
```
![Ejemplo de grid](./img/grid.jpg)



