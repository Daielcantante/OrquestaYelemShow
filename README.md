<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>La Orquesta Yelem Show</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            background-color: #f0f0f0;
            font-family: 'Arial', sans-serif;
        }
        .jumbotron {
            background-color: #022d41;
            color: white;
            padding: 2rem 1rem;
            margin-bottom: 2rem;
            background-image: url('tu-imagen-de-fondo.jpg');
            background-size: cover;
            text-shadow: 2px 2px 4px #000000;
        }
        .featurette-divider {
            margin: 5rem 0;
        }
        .featurette-heading {
            font-weight: 300;
            line-height: 1;
            letter-spacing: -0.05rem;
        }
        .gallery {
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            padding: 15px;
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
            margin-top: 20px;
        }
        .video-container iframe,
        .video-container object,
        .video-container embed {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .social-media-links {
            text-align: center;
            margin-top: 20px;
        }
        .social-media-links a {
            margin: 0 10px;
        }
    </style>
</head>
<body>

    <div class="jumbotron jumbotron-fluid text-center">
        <div class="container">
            <h1 class="display-4">La Orquesta Yelem Show</h1>
            <p class="lead">Una experiencia única donde la música se convierte en magia.</p>
        </div>
    </div>

    <div class="container">
        <div class="row featurette">
            <div class="col-md-7">
                <h2 class="featurette-heading">Sobre Nosotros. <span class="text-muted">Conoce la magia.</span></h2>
                <p class="lead">Con 13 componentes en escena, ofrecemos un espectáculo vibrante con una logística completa: sonido de alta potencia, luces deslumbrantes, y mucho más.</p>
            </div>
            <div class="col-md-5">
                <img src="tu-imagen-destacada.jpg" class="bd-placeholder-img bd-placeholder-img-lg featurette-image img-fluid mx-auto" width="500" height="500" alt="Imagen destacada">
            </div>
        </div>

        <hr class="featurette-divider">

        <!-- Sección de video -->
        <div class="row">
            <div class="col-lg-12">
                <h2 class="featurette-heading text-center">Mira Nuestra Actuación</h2>
                <div class="video-container">
                    <iframe src="https://www.youtube.com/embed/gZ-frJP8L98" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </div>
        </div>

        <hr class="featurette-divider">

        <!-- Enlaces a redes sociales -->
        <div class="social-media-links">
            <h3>Síguenos en nuestras redes</h3>
            <a href="https://www.instagram.com/orquestayelemshow_/" target="_blank" rel="noopener noreferrer">Instagram</a>
        </div>

        <hr class="featurette-divider">

        <div class="gallery row">
            <div class="col-md-4">
                <img src="foto1.jpg" alt="Foto 1">
            </div>
            <div class="col-md-4">
                <img src="foto2.jpg" alt="Foto 2">
            </div>
            <div class="col-md-4">
                <img src="foto3.jpg" alt="Foto 3">
            </div>
            <!-- Añade más fotos según sea necesario -->
        </div>

        <hr class="featurette-divider">

        <div class="row">
            <!-- Sección de contacto -->
        </div>
    </div>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
