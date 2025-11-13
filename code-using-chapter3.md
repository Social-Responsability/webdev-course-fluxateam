# 📄 Capítulo 3: Elementos HTML comunes

Esta lección cubre los elementos esenciales para enriquecer tu web: imágenes, enlaces, navegación interna, tablas y formularios.

---

### 🧪 Ejemplo 1 – Imágenes desde internet

```html
<h2>Imágenes desde internet</h2>
<img src="[https://images.dog.ceo/breeds/shiba/shiba-17.jpg](https://images.dog.ceo/breeds/shiba/shiba-17.jpg)"
     alt="Perro Shiba Inu"
     width="400">
```
---

### 🧪 Ejemplo 2 – Imagen con estilos avanzados
```html
<img src="[https://i.imgur.com/8p5z3Kg.jpg](https://i.imgur.com/8p5z3Kg.jpg)"
     alt="Gatito programando"
     width="500"
     style="display:block; margin:20px auto; border-radius:20px;">
```
---

### 🧪 Ejemplo 3 – Enlaces que molan
```html
<h2>Enlaces que molan</h2>

<a href="[https://youtube.com](https://youtube.com)" target="_blank">YouTube (abre nueva pestaña)</a>

<br /><br />

<a href="[https://codepen.io](https://codepen.io)">CodePen → El mejor editor online</a>
```
---

### 🧪 Ejemplo 4 – Navegación interna (Anclas)
```html
<nav>
  <a href="#inicio">Inicio</a> |
  <a href="#lista">Listas</a> |
  <a href="#form">Formulario</a>
</nav>

<div id="inicio" style="height:600px;">
  <h1>🏠 INICIO</h1>
</div>

<div id="lista" style="height:600px; background:#f0f0f0;">
  <h1>📋 LISTAS</h1>
  </div>
```
---

### 🧪 Ejemplo 5 – Tabla de YouTubers
```html
<h2>Tabla de YouTubers</h2>

<table border="1" style="width:100%; text-align:center; border-collapse:collapse;">
  <tr style="background:#333; color:white;">
    <th>Nombre</th>
    <th>Canal</th>
    <th>Suscriptores</th>
  </tr>
  <tr>
    <td>Fazt</td>
    <td>Fazt Code</td>
    <td>1.2M</td>
  </tr>
  <tr style="background:#f9f9f9;">
    <td>Bluuweb</td>
    <td>Bluuweb</td>
    <td>500K</td>
  </tr>
</table>
```
---

### 🧪 Ejemplo 6 – Formulario de contacto
```html
<div id="form" style="padding:50px; background:#222; color:white;">
  <h2>📧 Formulario de contacto</h2>

  <form action="[https://formspree.io/f/tu-email](https://formspree.io/f/tu-email)" method="POST">
    <label>Nombre:</label><br>
    <input type="text" name="nombre" placeholder="Tu nombre" required><br>

    <label>Email:</label><br>
    <input type="email" name="email" placeholder="tu@email.com" required><br>

    <label>Mensaje:</label><br>
    <textarea name="mensaje" rows="5" placeholder="Escribe aquí..." required></textarea><br>

    <button type="submit">🚀 ENVIAR MENSAJE</button>
  </form>

  <p><small>Funciona 100% real con Formspree (gratis)</small></p>
</div>
```
---
