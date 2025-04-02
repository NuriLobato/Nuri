<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Tu Nombre</h1>
        <nav>
            <ul>
                <li><a href="#about">Sobre mí</a></li>
                <li><a href="#projects">Proyectos</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Sobre Mí</h2>
        <p>Hola, soy [Tu Nombre], estudiante de audiovisuales con experiencia en edición de video...</p>
    </section>

    <section id="projects">
        <h2>Proyectos</h2>
        <div class="project">
            <h3>Proyecto 1</h3>
            <p>Descripción del proyecto.</p>
        </div>
        <div class="project">
            <h3>Proyecto 2</h3>
            <p>Descripción del proyecto.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>Email: tuemail@gmail.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Tu Nombre</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
    text-align: center;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 20px auto;
    max-width: 800px;
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background-color: #333;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
