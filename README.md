<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Corazones Solidarios - Fotografía de Mascotas y Adopción Responsable</title>
    <!-- Bootstrap 5 CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Custom CSS -->
    <style>
        :root {
            --beige: #F5F5DC;
            --brown: #8B4513;
            --black: #000000;
        }

        body {
            background-color: var(--beige);
            color: var(--black);
            font-family: Arial, sans-serif;
        }

        .navbar {
            background-color: var(--brown);
        }

        .navbar-brand, .nav-link {
            color: var(--beige) !important;
        }

        .nav-link:hover {
            color: var(--black) !important;
        }

        .hero-section {
            background-image: url('https://via.placeholder.com/1920x600?text=Hero+Image+Pet+Photography');
            background-size: cover;
            background-position: center;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: var(--beige);
            text-shadow: 2px 2px 4px var(--black);
        }

        .section-title {
            color: var(--brown);
            text-align: center;
            margin-bottom: 2rem;
        }

        .card {
            background-color: var(--beige);
            border: 2px solid var(--brown);
            color: var(--black);
        }

        .card-img-top {
            height: 200px;
            object-fit: cover;
        }

        .btn-primary {
            background-color: var(--brown);
            border-color: var(--brown);
            color: var(--beige);
        }

        .btn-primary:hover {
            background-color: var(--black);
            border-color: var(--black);
        }

        .social-icons a {
            color: var(--brown);
            font-size: 2rem;
            margin: 0 1rem;
        }

        .social-icons a:hover {
            color: var(--black);
        }

        footer {
            background-color: var(--brown);
            color: var(--beige);
            padding: 2rem 0;
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            height: 0;
            overflow: hidden;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Corazones Solidarios</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">Sobre Nosotros</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#gallery">Galería</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#adoption">Adopción</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#contact">Contacto</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-section">
        <div>
            <h1>Corazones Solidarios</h1>
            <p>Sesiones fotográficas con mascotas y promoción de adopción responsable</p>
            <a href="#contact" class="btn btn-primary btn-lg">Contáctanos</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-5">
        <div class="container">
            <h2 class="section-title">Sobre Nosotros</h2>
            <p>Corazones Solidarios es un proyecto dedicado a capturar la belleza y el amor de las mascotas a través de sesiones fotográficas profesionales. Trabajamos con dueños de mascotas para crear recuerdos inolvidables y colaboramos con el albergue Génesis para promover la adopción responsable de animales en busca de un hogar. Nuestra misión es unir corazones a través del amor por los animales.</p>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Galería de Fotos y Videos</h2>
            <div class="row">
                <!-- Photo 1 -->
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/400x200?text=Perro+Feliz" class="card-img-top" alt="Perro Feliz">
                        <div class="card-body">
                            <h5 class="card-title">Sesión con Max</h5>
                            <p class="card-text">Una sesión divertida con Max, un labrador lleno de energía.</p>
                        </div>
                    </div>
                </div>
                <!-- Photo 2 -->
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/400x200?text=Gato+Juguetón" class="card-img-top" alt="Gato Juguetón">
                        <div class="card-body">
                            <h5 class="card-title">Sesión con Luna</h5>
                            <p class="card-text">Luna, una gata elegante, capturada en su mejor momento.</p>
                        </div>
                    </div>
                </div>
                <!-- Video -->
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <div class="video-container">
                            <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Pet Video" frameborder="0" allowfullscreen></iframe>
                        </div>
                        <div class="card-body">
                            <h5 class="card-title">Video de Adopción</h5>
                            <p class="card-text">Conoce a nuestros amigos en el albergue Génesis.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Adoption Section -->
    <section id="adoption" class="py-5">
        <div class="container">
            <h2 class="section-title">Adopción Responsable</h2>
            <p>Colaboramos con el albergue Génesis para encontrar hogares amorosos para mascotas necesitadas. Adopting a pet is a big responsibility, but it’s also a rewarding experience. Learn more about the adoption process and meet some of our adoptable pets.</p>
            <a href="https://www.example.com/adoption" class="btn btn-primary">Conoce a las Mascotas</a>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5 bg-light">
        <div class="container">
            <h2 class="section-title">Contáctanos</h2>
            <p>¿Listo para una sesión fotográfica con tu mascota o interesado en adoptar? ¡Contáctanos!</p>
            <div class="social-icons text-center mb-4">
                <!-- TikTok Link -->
                <a href="https://www.tiktok.com/@corazonessolidarios" target="_blank">
                    <i class="fab fa-tiktok"></i>
                </a>
                <!-- WhatsApp Link -->
                <a href="https://wa.me/1234567890?text=Hola%20Corazones%20Solidarios,%20quiero%20información%20sobre%20sesiones%20fotográficas%20o%20adopción" target="_blank">
                    <i class="fab fa-whatsapp"></i>
                </a>
            </div>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Nombre</label>
                    <input type="text" class="form-control" id="name" placeholder="Tu nombre">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Correo Electrónico</label>
                    <input type="email" class="form-control" id="email" placeholder="Tu correo">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Mensaje</label>
                    <textarea class="form-control" id="message" rows="4" placeholder="Tu mensaje"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Enviar</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="text-center">
        <div class="container">
            <p>&copy; 2025 Corazones Solidarios. Todos los derechos reservados.</p>
            <p>En colaboración con el albergue Génesis.</p>
        </div>
    </footer>

    <!-- Bootstrap 5 JS and Font Awesome for Icons -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>

    <!-- GitHub Upload Instructions -->
    <!--
    Instrucciones para subir a GitHub:
    1. Crea una cuenta en GitHub (https://github.com) si no tienes una.
    2. Crea un nuevo repositorio:
       - Haz clic en "New repository" en tu perfil de GitHub.
       - Nombra el repositorio, por ejemplo, "corazones-solidarios".
       - Selecciona "Public" para que sea accesible.
       - Opcionalmente, inicializa con un README.
    3. Sube el archivo index.html:
       - Descarga este archivo HTML en tu computadora.
       - En el repositorio, haz clic en "Add file" > "Upload files".
       - Arrastra y suelta el archivo index.html o selecciona desde tu computadora.
       - Haz clic en "Commit changes".
    4. Habilita GitHub Pages:
       - Ve a la pestaña "Settings" de tu repositorio.
       - Desplázate a la sección "Pages".
       - En "Source", selecciona "main" branch y la carpeta "/ (root)".
       - Haz clic en "Save". Tu sitio estará disponible en https://tu-usuario.github.io/corazones-solidarios/.
    5. Personaliza:
       - Reemplaza las imágenes y videos con tus propios archivos (sube tus imágenes a una carpeta "images" en el repositorio).
       - Actualiza los enlaces de TikTok y WhatsApp con tus cuentas reales.
       - Modifica el enlace de adopción para dirigir al sitio del albergue Génesis.
    -->
</body>
</html>