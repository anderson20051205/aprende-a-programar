<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aprende a Programar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #77b300 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .main {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Aprende a Programar</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#lenguajes">Lenguajes</a></li>
                    <li><a href="#recursos">Recursos</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <div class="container main" id="inicio">
        <h2>Bienvenido a Aprende a Programar</h2>
        <p>En esta página encontrarás recursos y guías para comenzar tu viaje en el mundo de la programación. Desde lenguajes populares hasta herramientas y comunidades, todo lo que necesitas para empezar está aquí.</p>
    </div>
    <div class="container main" id="lenguajes">
        <h2>Lenguajes de Programación</h2>
        <h3>Python</h3>
        <p>Python es un lenguaje de programación popular por su simplicidad y versatilidad. Es ideal para principiantes y se utiliza en diversos campos como desarrollo web, ciencia de datos, inteligencia artificial y más.</p>
        <h3>JavaScript</h3>
        <p>JavaScript es el lenguaje de la web. Es fundamental para el desarrollo web frontend y se utiliza para crear sitios web interactivos y dinámicos.</p>
        <h3>Java</h3>
        <p>Java es un lenguaje de programación robusto y orientado a objetos que es ampliamente utilizado en el desarrollo de aplicaciones empresariales y aplicaciones móviles (especialmente Android).</p>
        <h3>C++</h3>
        <p>C++ es un lenguaje poderoso que se utiliza en el desarrollo de sistemas operativos, videojuegos y aplicaciones de alto rendimiento. Ofrece control sobre el hardware y memoria del sistema.</p>
    </div>
    <div class="container main" id="recursos">
        <h2>Recursos Útiles</h2>
        <ul>
            <li><a href="https://www.codecademy.com/learn/learn-python-3" target="_blank">Codecademy - Aprende Python</a></li>
            <li><a href="https://www.freecodecamp.org/learn" target="_blank">freeCodeCamp - Aprende JavaScript</a></li>
            <li><a href="https://www.coursera.org/specializations/java-programming" target="_blank">Coursera - Especialización en Programación en Java</a></li>
            <li><a href="https://www.learncpp.com/" target="_blank">LearnCpp - Aprende C++</a></li>
        </ul>
    </div>
    <footer>
        <p>Aprende a Programar &copy; 2024</p>
    </footer>
</body>
</html>

