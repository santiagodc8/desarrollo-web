# 📌 Estructura básica de un documento HTML
```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página</title>
</head>
<body>
    <h1>¡Hola, mundo!</h1>
</body>
</html>
```

---

# 🏗 Etiquetas de estructura
| Etiqueta | Descripción |
|----------|------------|
| `<html>` | Contenedor principal de la página. |
| `<head>` | Contiene metadatos, enlaces a CSS, scripts, etc. |
| `<body>` | Contiene todo el contenido visible. |
| `<title>` | Define el título de la página. |
| `<meta>` | Define metadatos como el charset o viewport. |

---

# 🔤 Etiquetas de texto y formato
| Etiqueta | Descripción |
|----------|------------|
| `<h1>` - `<h6>` | Encabezados (de mayor a menor importancia). |
| `<p>` | Párrafo de texto. |
| `<b>` | Texto en **negrita**. |
| `<i>` | Texto en *cursiva*. |
| `<u>` | Texto **subrayado**. |
| `<strong>` | Texto importante (negrita semántica). |
| `<em>` | Texto enfatizado (cursiva semántica). |
| `<br>` | Salto de línea. |
| `<hr>` | Línea horizontal divisoria. |

---

# 🔗 Enlaces e imágenes
| Etiqueta | Descripción |
|----------|------------|
| `<a href="url">` | Crea un enlace. |
| `<img src="imagen.jpg" alt="Descripción">` | Muestra una imagen. |
| `<figure>` y `<figcaption>` | Agrupan imágenes y agregan una descripción. |

---

# 📋 Listas
```html
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>

<ol>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ol>
```

---

# 🏠 Estructura de la página (HTML5)
| Etiqueta | Descripción |
|----------|------------|
| `<header>` | Encabezado de la página. |
| `<nav>` | Menú de navegación. |
| `<section>` | Sección de contenido. |
| `<article>` | Contenido independiente. |
| `<aside>` | Contenido secundario. |
| `<footer>` | Pie de página. |
| `<main>` | Contenido principal. |
| `<div>` | Contenedor genérico. |
| `<span>` | Contenedor en línea. |

---

# 🔲 Tablas
```html
<table border="1">
    <thead>
        <tr>
            <th>Nombre</th>
            <th>Edad</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Juan</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```

---

# 🔘 Formularios e inputs
```html
<form action="/enviar" method="POST">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre" required>
    
    <button type="submit">Enviar</button>
</form>
```

---

# 🎬 Multimedia
```html
<video controls>
    <source src="video.mp4" type="video/mp4">
</video>
