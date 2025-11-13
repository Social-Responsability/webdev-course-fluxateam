# 📄 Capítulo 5: Estilo simple con CSS

Esta lección profundiza en el diseño de contenedores, bordes, márgenes y la alineación de elementos.

---

### 🧪 Ejemplo 1 – Alineación en contenedores
```html
<div class="contenedor">
  <h1>Bienvenido</h1>
  <p>Este texto está centrado con CSS.</p>
</div>
```
```css
/* CSS */
.contenedor {
  text-align: center;
}
```
---

### 🧪 Ejemplo 2 – Colores y espaciado básico
```css
/* CSS */
body {
  background-color: #f0f0f0;
}

h1 {
  color: darkblue;
}

p {
  color: #333;
  background-color: #fff;
  padding: 10px;
}
```
---

### 🧪 Ejemplo 3 – Bordes y márgenes
```css
/* CSS */
.contenedor {
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
```
---

### 🧪 Ejemplo 4 – Estilos de borde avanzados
```css
/* CSS */
p {
  border: 3px dashed red;
  border-radius: 10px;
}
```
---

### 🧪 Ejemplo 5 – Estilo completo combinado
```html
<div class="contenedor">
  <h1>Mi página con estilo simple</h1>
  <p>Este párrafo está centrado, con fondo blanco, borde rojo y esquinas redondeadas.</p>
</div>
```

```css
/* CSS */
body {
  background-color: #fafafa;
  font-family: Arial, sans-serif;
}

.contenedor {
  text-align: center;
  border: 2px solid black;
  margin: 30px auto; /* auto centra el contenedor horizontalmente */
  padding: 20px;
  width: 60%;
  background-color: #fff;
}

h1 {
  color: darkblue;
}

p {
  color: #333;
  border: 3px dashed red;
  border-radius: 10px;
  padding: 15px;
}
```
---
