# 📄 Capítulo 4: Introducción a CSS

Esta lección introduce las hojas de estilo en cascada (CSS) para dar color, diseño y formato a tu HTML.

---

### 🧪 Ejemplo 1 – Colores básicos
```html
/* HTML */
<h1>Bienvenido a mi página</h1>
<p>Este es un párrafo normal.</p>
```
```css
/* CSS */
h1 {
  color: red;
}

p {
  color: blue;
}
```
---

### 🧪 Ejemplo 2 – Estilos de página y texto
```css
/* CSS */
body {
  background-color: #f0f0f0;
}

h1 {
  text-align: center;
  font-size: 32px;
}

p {
  font-size: 18px;
  line-height: 1.5;
}
```
---

### 🧪 Ejemplo 3 – Clases y IDs
```html
/* HTML */
<p class="destacado">Este párrafo está destacado.</p>
<p id="especial">Este párrafo es único.</p>
```
```css
/* CSS */
.destacado {
  background-color: yellow;
  font-weight: bold;
}

#especial {
  color: purple;
  font-style: italic;
}
```
---

### 🧪 Ejemplo 4 – Tipografía y alineación
```css
/* CSS */
body {
  font-family: Arial, sans-serif;
  margin: 20px;
}

h1 {
  color: darkblue;
  text-transform: uppercase;
}

p {
  color: #333333;
  text-align: justify;
}
```
---

### 🧪 Ejemplo 5 – Estructura completa con estilos
```html
/* HTML */
<h1>Mi primera página con CSS</h1>

<p>Este es un párrafo normal.</p>

<p class="destacado">Este párrafo está destacado con fondo amarillo.</p>

<p id="especial">Este párrafo es único y está en cursiva.</p>
```

```css
/* CSS */
body {
  font-family: Verdana, sans-serif;
  background-color: #fafafa;
  margin: 30px;
}

h1 {
  text-align: center;
  color: darkred;
}

p {
  font-size: 16px;
  line-height: 1.6;
  color: #444;
}

.destacado {
  background-color: yellow;
  padding: 10px;
}

#especial {
  color: purple;
  font-style: italic;
}
```
---
