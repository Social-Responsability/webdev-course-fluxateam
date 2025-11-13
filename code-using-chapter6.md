# 📄 Capítulo 6: Crear una web completa

Esta lección combina todo lo aprendido para construir un proyecto final: una tarjeta de perfil personal con diseño profesional, sombras y estilos interactivos.

---

### 🧪 Ejemplo 5 – Proyecto Final: Perfil Personal

```html
<div class="perfil">
  <h1>PROGRAMADOR INCÓGNITO - DESARROLLADOR</h1>

  <img src="[https://cdn-icons-png.flaticon.com/512/4792/4792929.png](https://cdn-icons-png.flaticon.com/512/4792/4792929.png)" 
       alt="Foto de perfil" 
       class="foto" 
       width="150">

  <p>¡Hola! Soy el programador incógnito y me gusta enseñar HTML y CSS de forma práctica y clara.</p>

  <h2>Mis hobbies</h2>
  <ul>
    <li>Programar proyectos creativos</li>
    <li>Leer sobre innovación</li>
    <li>Compartir conocimiento</li>
  </ul>

  <h2>Contacto</h2>
  <p>Puedes escribirme a <a href="mailto:programadorincognito@gmail.com">mi correo</a>.</p>
</div>
```

```css
/* CSS */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
  margin: 0;
  padding: 0;
}

.perfil {
  width: 60%;
  margin: 40px auto;
  text-align: center;
  background-color: #fff;
  border: 2px solid #ddd;
  border-radius: 15px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.foto {
  border-radius: 50%;
  border: 3px solid #333;
  margin: 20px 0;
}

h1 {
  color: darkblue;
}

h2 {
  color: #444;
  margin-top: 20px;
}

p {
  color: #555;
  line-height: 1.6;
}

a {
  color: darkred;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}
```
---
