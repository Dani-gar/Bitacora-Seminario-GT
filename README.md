# Bitacora-Seminario-GT
bitacora de las clases de seminario de gestion tecnologica 2024-2


---

### Archivo: `index.html`
Este es el archivo principal de tu página web.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bitácora - Seminario Gestión Tecnológica</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</head>
<body>
    <header class="bg-primary text-white text-center py-4">
        <h1>Seminario Gestión Tecnológica</h1>
        <p>Bitácora del curso</p>
    </header>

    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Inicio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link" href="#contenido">Contenido</a></li>
                    <li class="nav-item"><a class="nav-link" href="#conclusiones">Conclusiones</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <main class="container my-4">
        <section id="contenido">
            <h2>Contenido</h2>
            <p>Aquí encontrarás un resumen de los temas tratados en el seminario, como protocolos, políticas públicas, historia de la industria, bases de datos, y más.</p>
        </section>

        <section id="conclusiones">
            <h2>Conclusiones</h2>
            <p>El seminario destacó la importancia de la innovación, la tecnología, y el análisis histórico para el desarrollo económico y social.</p>
        </section>

        <section id="contacto">
            <h2>Contacto</h2>
            <p>Para más información, escribe a: <a href="mailto:correo@ejemplo.com">correo@ejemplo.com</a></p>
        </section>
    </main>

    <footer class="text-center py-3 bg-dark text-white">
        <p>© 2024 Seminario Gestión Tecnológica</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

---

### Archivo: `css/styles.css`
Guarda este archivo en una carpeta llamada `css`.

```css
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

h1, h2 {
    font-weight: bold;
}

nav a {
    color: #000;
    text-decoration: none;
}

nav a:hover {
    text-decoration: underline;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
}
```

---

### Organización para GitHub
Asegúrate de que la estructura de tus archivos sea como esta:

```
/seminario-tecnologico
  ├── index.html
  └── /css
        └── styles.css
```

---
