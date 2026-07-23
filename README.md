# index.html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body{
            background:#f4f4f4;
            color:#333;
        }

        header{
            background:#0078D7;
            color:white;
            padding:20px;
            text-align:center;
        }

        nav{
            background:#005fa3;
            padding:10px;
            text-align:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin:0 15px;
            font-weight:bold;
        }

        nav a:hover{
            text-decoration:underline;
        }

        main{
            max-width:1000px;
            margin:30px auto;
            padding:20px;
            background:white;
            border-radius:10px;
            box-shadow:0 0 10px rgba(0,0,0,0.1);
        }

        section{
            margin-bottom:30px;
        }

        footer{
            background:#333;
            color:white;
            text-align:center;
            padding:15px;
            margin-top:30px;
        }

        button{
            background:#0078D7;
            color:white;
            border:none;
            padding:10px 20px;
            border-radius:5px;
            cursor:pointer;
            margin-top:10px;
        }

        button:hover{
            background:#005fa3;
        }
    </style>
</head>
<body>

    <header>
        <h1>Bienvenido a Mi Página Web</h1>
        <p>Plantilla HTML básica</p>
    </header>

    <nav>
        <a href="#">Inicio</a>
        <a href="#">Servicios</a>
        <a href="#">Acerca de</a>
        <a href="#">Contacto</a>
    </nav>

    <main>
        <section>
            <h2>Inicio</h2>
            <p>
                Esta es una plantilla HTML predeterminada. Puedes modificar el
                contenido, los colores y agregar más secciones según tus necesidades.
            </p>

            <button onclick="saludar()">Haz clic</button>
        </section>

        <section>
            <h2>Servicios</h2>
            <ul>
                <li>Diseño Web</li>
                <li>Desarrollo Web</li>
                <li>Soporte Técnico</li>
            </ul>
        </section>

        <section>
            <h2>Contacto</h2>
            <p>Correo: ejemplo@correo.com</p>
            <p>Teléfono: +00 123 456 789</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Mi Página Web. Todos los derechos reservados.</p>
    </footer>

    <script>
        function saludar() {
            alert("¡Hola! Bienvenido a la página.");
        }
    </script>

</body>
</html>
