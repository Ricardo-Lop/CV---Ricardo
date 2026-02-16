Pagina BASE
JARAMILLO VELASCO RICARDO
•
9:40
02-cv-base.html
HTML

Comentarios de la clase

Añade un comentario de clase…

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - [TU NOMBRE]</title>
    <!-- DESAFÍO PLUS: Añadir favicon aquí -->
</head>
<body>

    <!-- ====================
         HEADER: Tu nombre y título profesional
         ==================== -->
    <header>
        <!-- COMPLETAR: Tu nombre completo -->
        <h1>Ricardo Mercado López</h1>

        <!-- COMPLETAR: Tu título profesional o lo que estudias -->
        <p>Estudiante de Ingeniería Software</p>
    </header>

    <!-- ====================
         MAIN: Contenido principal del CV
         ==================== -->
    <main>

        <!-- SECCIÓN: Sobre Mí -->
        <section id="sobre-mi">
            <h2>Sobre Mí</h2>

            <!-- COMPLETAR: Breve descripción de ti (2-4 líneas) -->
            <p>
                Soy estudiante de la Facultad de Telematica, me gusta la programación y crear páginas web
            </p>

            <!-- OPCIONAL: Segundo párrafo si necesitas más espacio
              <p>
                  [Puedes mencionar tus intereses, metas profesionales, etc.]
              </p>-->
        </section>

        <!-- SECCIÓN: Experiencia / Educación -->
        <section id="experiencia">
            <h2>Experiencia y Educación</h2>

            <!-- Usamos una lista desordenada para items -->
            <ul>
                <!-- COMPLETAR: Item 1 -->
                <li>
                    <strong>Bachillerato 1</strong> - 2021 - 2024
                    <br>
                    En 4° y 5° semestre de bachillerato me metí a ingeniería donde aprendí a programar y a crear páginas web, también aprendí a trabajar
                    <br> en equipo y a usar herramientas de control de versiones como GitHub
                </li>

                <!-- COMPLETAR: Item 2
                        <li>
                            <strong>[Título/Institución]</strong> - [Año o período]
                            <br>
                            [Breve descripción]
                        </li>

                         COMPLETAR: Item 3 (opcional)
                        <li>
                            <strong>[Título/Institución]</strong> - [Año o período]
                            <br>
                            [Breve descripción]
                        </li>
                    </ul>
                </section>

                 SECCIÓN: Habilidades -->
                <section id="habilidades">
                    <h2>Habilidades</h2>

                    <!-- COMPLETAR: Lista de habilidades -->
                    <ul>
                        <li>Conocimiento básico de html</li>
                        <li>Trabajo en equipo</li>
                        <li>Uso de herramientas de control de versiones como GitHub</li>
                    </ul>
                </section>

                <!-- SECCIÓN: Contacto (Formulario) -->
                <section id="contacto">
                    <h2>Contacto</h2>

                    <!--
                        FORMULARIO HTML5 CON VALIDACIÓN NATIVA
                        Nota: Esto no envía emails aún (necesita backend),
                        pero valida que los datos sean correctos
                    -->
                    <form action="#" method="post">

                        <!-- Campo de Email con validación automática -->
                        <p>
                            <label for="email">Tu Email:</label><br>
                            <input type="email"
                                   id="email"
                                   name="email"
                                   placeholder="ejemplo@correo.com"
                                   required>
                        </p>

                        <!-- Campo de Nombre (requerido) -->
                        <p>
                            <label for="nombre">Tu Nombre:</label><br>
                            <input type="text"
                                   id="nombre"
                                   name="nombre"
                                   placeholder="¿Quién eres?"
                                   required
                                   minlength="2">
                        </p>

                        <!-- Campo de Mensaje -->
                        <p>
                            <label for="mensaje">Mensaje:</label><br>
                            <textarea id="mensaje"
                                      name="mensaje"
                                      rows="4"
                                      cols="50"
                                      placeholder="Escribe tu mensaje aquí..."
                                      required
                                      minlength="10"></textarea>
                        </p>

                        <!-- Botón de envío -->
                        <button type="submit">Enviar Mensaje</button>

                    </form>

                    <!-- Información de contacto directo -->
                    <p>
                        <strong>Email directo:</strong> [rmercad0@ucol.mx]<br>
                        <strong>Teléfono:</strong> [312-123-4567]
                    </p>
                </section>

    </main>

    <!-- ====================
         FOOTER: Pie de página
         ==================== -->
    <footer>
        <p>&copy; 2024 Ricardo Mercado. CV creado con HTML5.</p>

        <!-- OPCIONAL: Enlace a tu GitHub -->
        <p>
            <a href="https://github.com/Ricardo-Lop" target="_blank">
                Ver mi GitHub
            </a>
        </p>
    </footer>

</body>
</html>
