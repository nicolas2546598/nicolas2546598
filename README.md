<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Agencia de Marketing</title>
    <!-- Enlace a la fuente VolteRounded-Light -->
    <style>
        @font-face {
            font-family: 'VolteRounded-Light';
            src: url('ruta/a/tu/fuente/VolteRounded-Light.woff2') format('woff2'),
                 url('ruta/a/tu/fuente/VolteRounded-Light.woff') format('woff');
            font-weight: normal;
            font-style: normal;
        }
        body {
            font-family: 'VolteRounded-Light', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #f9f9f9;
            line-height: 1.6;
        }
        header {
            background: url('ruta/a/tu/imagen-destacada.jpg') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 5rem 0;
        }
        header h1 {
            margin: 0;
            font-size: 3rem;
        }
        header p {
            font-size: 1.25rem;
        }
        section {
            padding: 2rem 1rem;
            max-width: 1200px;
            margin: auto;
        }
        section h2 {
            text-align: center;
            margin-bottom: 1rem;
            font-size: 2rem;
        }
        .services, .portfolio, .testimonials {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .service, .project, .testimonial {
            background: white;
            border: 1px solid #ddd;
            padding: 1rem;
            width: calc(33% - 2rem);
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            gap: 1rem;
            max-width: 600px;
            margin: auto;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 0.5rem;
            border: 1px solid #ddd;
        }
        .contact-form button {
            padding: 0.75rem;
            background: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #333;
            color: white;
        }
    </style>
</head>
<body>
    <!-- Página de Inicio -->
    <header id="inicio">
        <h1>Impulsando tu marca al siguiente nivel</h1>
        <p>Especialistas en marketing digital y estrategias innovadoras</p>
    </header>

    <!-- Sobre Nosotros -->
    <section id="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>Somos una agencia de marketing apasionada por ayudar a nuestros clientes a alcanzar sus objetivos a través de estrategias innovadoras y personalizadas.</p>
        <div id="equipo">
            <h3>Conoce a Nuestro Equipo</h3>
            <!-- Añadir detalles del equipo aquí -->
        </div>
    </section>

    <!-- Servicios -->
    <section id="servicios">
        <h2>Nuestros Servicios</h2>
        <div class="services">
            <div class="service">
                <h3>Marketing Digital</h3>
                <p>Creación de estrategias digitales que impulsan tu negocio.</p>
            </div>
            <div class="service">
                <h3>SEO</h3>
                <p>Optimización de tu sitio web para mejorar su visibilidad en motores de búsqueda.</p>
            </div>
            <div class="service">
                <h3>Gestión de Redes Sociales</h3>
                <p>Manejo y creación de contenido para tus redes sociales.</p>
            </div>
            <!-- Añadir más servicios aquí -->
        </div>
    </section>

    <!-- Portafolio -->
    <section id="portafolio">
        <h2>Portafolio</h2>
        <div class="portfolio">
            <div class="project">
                <h3>Proyecto Destacado 1</h3>
                <p>Campaña de marketing digital para [Cliente X] que incrementó su visibilidad en un 200%.</p>
            </div>
            <div class="project">
                <h3>Proyecto Destacado 2</h3>
                <p>Estrategia de SEO para [Cliente Y] que mejoró su ranking de búsqueda.</p>
            </div>
            <div class="project">
                <h3>Proyecto Destacado 3</h3>
                <p>Gestión de redes sociales para [
