<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio de Anthony Goyes</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Estilo general */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            color: #333;
        }

        /* Encabezado */
        header {
            background-color: #4a90e2;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        /* Menú de navegación */
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 15px 20px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #575757;
        }

        /* Imagen circular */
        .imagen-circular {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            overflow: hidden;
            margin: 20px auto;
        }

        .imagen-circular img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Secciones */
        section {
            background-color: white;
            margin: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            color: #4a90e2;
            margin-top: 0;
        }

        /* Lista de habilidades y proyectos */
        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin: 10px 0;
        }

        /* Botones de enlace */
        a.button {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 10px;
            background-color: #4a90e2;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        a.button:hover {
            background-color: #357ab8;
        }

        /* Animación sutil */
        section {
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px;
            background-color: #333;
            color: white;
            position: fixed;
            width: 100%;
            bottom: 0;
        }

        footer a {
            color: #4a90e2;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Encabezado -->
    <header>
        <h1>¡Hola! 👋 Soy Anthony Goyes</h1>
        <p>Bienvenido a mi portafolio en GitHub</p>
    </header>

    <!-- Menú de navegación -->
    <nav>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#habilidades">Habilidades</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <!-- Imagen -->
    <div class="imagen-circular">
        <img src="ImagenGithub.png" alt="Foto de Anthony Goyes">
    </div>

    <!-- Sección Sobre mí -->
    <section id="sobre-mi">
        <h2>Sobre mí</h2>
        <p>
            Soy estudiante de quinto semestre de Ingeniería en Ciencias de la Computación en la Escuela Politécnica Nacional, apasionado por la tecnología y la creación de soluciones innovadoras.
            Me destaco por mi capacidad para trabajar bajo presión, aprender de mis errores y generar un impacto positivo a través de la tecnología.
        </p>
    </section>

    <!-- Sección Habilidades -->
    <section id="habilidades">
        <h2>Habilidades</h2>
        <ul>
            <li><i class="fas fa-code"></i> Lenguajes de programación: Python, C++, Java</li>
            <li><i class="fas fa-database"></i> Bases de Datos: SQL</li>
            <li><i class="fas fa-tools"></i> Herramientas: Microsoft Office</li>
            <li><i class="fas fa-network-wired"></i> Redes de computadoras: Fundamentos de redes</li>
            <li><i class="fas fa-language"></i> Idiomas: Inglés (certificado por EPN)</li>
        </ul>
    </section>

    <!-- Sección Proyectos -->
    <section id="proyectos">
        <h2>Proyectos</h2>
        <ul>
            <li>
                <strong>Implementación de una red para un hotel temático de Disney con dos sucursales</strong>
                <p>
                    - Este proyecto, realizado en grupo, consistió en la implementación de una red en Packet Tracer para un hotel temático de Disney con dos sucursales.<br>
                    - Contribuí al diseño y configuración de la red, así como a la interconexión de las sucursales para garantizar una comunicación fluida y segura entre ambas sedes. <br>
                    <a href="https://drive.google.com/file/d/1OIXNVtFKbT9qtU4WNRiKfsloTUz-fWMu/view?usp=sharing" class="button">Ver informe del proyecto</a>
                </p>
            </li>
            <li>
                <strong>Contador de estudiantes aprobados y reprobados en lenguaje MIPS Assembler</strong>
                <p>
                    - Desarrollo de un código en lenguaje MIPS Assembler que, dado un número de estudiantes y sus calificaciones, determinaba el número de estudiantes aprobados y reprobados. <br>
                    - Este proyecto me permitió profundizar mis conocimientos en lenguajes de bajo nivel y en la manipulación de datos. <br>
                    <a href="https://drive.google.com/file/d/1IGKHHFoKe2tfWKuxKIqmzTGUkRPcFQ_v/view?usp=sharing" class="button">Ver informe del proyecto</a>
                </p>
            </li>
            <li>
                <strong>Simulación de Trayectoria de un Nanodrón</strong>
                <p>
                    - Este proyecto, realizado en grupo, consistió en el desarrollo de un programa que simula la trayectoria de un nanodrón usando el método de Euler para resolver ecuaciones diferenciales de movimiento. <br>
                    - El programa permite la entrada de constantes y condiciones iniciales, y genera gráficos en 2D y 3D de la trayectoria del dron.<br>
                    <a href="https://github.com/anthonypgq/MN-Proyecto02-Nanodron" class="button">Enlace al proyecto</a>
                </p>
            </li>
            <li>
                <strong>Plataforma de Seguimiento de Salud Materna (Propuesta de Diseño)</strong>
                <p>
                    - Diseño de una interfaz de baja fidelidad (mockups) orientada al seguimiento de la salud materna con recordatorios y monitoreo de síntomas. <br>
                    - Colaboré en la elaboración de un plan de acción desde la investigación hasta la implementación teórica. <br>
                    <a href="https://docs.google.com/document/d/1W0Rm4DurpLym1bm1I-ujvrSVqP_QhOcaYfBphgg1_us/edit?usp=sharing" class="button">Ver informe del proyecto</a>
                </p>
            </li>
            <li>
                <strong>Base de Datos para Asociaciones No Gubernamentales</strong>
                <p>
                    - Creación de una base de datos para gestionar información de asociaciones no gubernamentales e implementación de consultas para facilitar el acceso y análisis de datos. <br>                    
                    <a href="https://drive.google.com/file/d/1roGH6tI6EgEZOlqW_bGZmF2fnzHU9z85/view?usp=sharing" class="button">Enlace al script del proyecto</a>
                </p>
            </li>
        </ul>
    </section>

    <!-- Sección Contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes encontrarme en <a href="https://github.com/anthonypgq" target="_blank">mi perfil de GitHub</a>.</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>Desarrollado por Anthony Goyes | <a href="https://github.com/anthonypgq">GitHub</a></p>
    </footer>

</body>
</html>

