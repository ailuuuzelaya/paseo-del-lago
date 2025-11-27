<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paseo del Lago - Complejo de Pádel y Buffet</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #e8f5e8, #e3f2fd); /* Fondo suave y vivo */
            color: #333;
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        header {
            background: linear-gradient(135deg, #4CAF50, #FF9800, #2196F3); /* Gradiente vibrante con naranja */
            color: white;
            padding: 50px 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            animation: slideDown 1s ease-out;
        }
        @keyframes slideDown {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        header h1 {
            font-size: 3em;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            padding: 5px 10px;
            border-radius: 5px;
        }
        nav a:hover {
            background-color: #FF9800; /* Naranja vibrante en hover */
            color: #333;
            transform: scale(1.1);
        }
        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .hero {
            background-image: url('https://via.placeholder.com/1200x400/4CAF50/FFFFFF?text=Pádel+en+Paseo+del+Lago'); /* Imagen placeholder */
            background-size: cover;
            background-position: center;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
            position: relative;
        }
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(255, 152, 0, 0.3); /* Overlay naranja para más vida */
            z-index: 1;
        }
        .hero div {
            position: relative;
            z-index: 2;
        }
        .hero h2 {
            font-size: 2.5em;
            animation: bounceIn 1.5s ease-out;
        }
        @keyframes bounceIn {
            0% { transform: scale(0.3); opacity: 0; }
            50% { transform: scale(1.05); }
            70% { transform: scale(0.9); }
            100% { transform: scale(1); opacity: 1; }
        }
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .feature {
            background: linear-gradient(135deg, #ffffff, #f0f8ff); /* Fondo blanco con toque azul */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin: 20px;
            padding: 20px;
            width: 300px;
            text-align: center;
            transition: all 0.3s ease;
            border: 2px solid transparent;
        }
        .feature:hover {
            transform: translateY(-10px) rotate(2deg);
            border-color: #FF9800; /* Borde naranja en hover */
            box-shadow: 0 8px 16px rgba(255, 152, 0, 0.3);
        }
        .feature h3 {
            color: #4CAF50;
            transition: color 0.3s;
        }
        .feature:hover h3 {
            color: #FF9800; /* Cambio a naranja */
        }
        footer {
            background: linear-gradient(135deg, #333, #555); /* Gradiente oscuro con vida */
            color: white;
            text-align: center;
            padding: 20px;
            animation: fadeInUp 1s ease-out;
        }
        @keyframes fadeInUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Paseo del Lago</h1>
        <p>Tu complejo deportivo de pádel y buffet moderno en Rauch, Provincia de Buenos Aires</p>
        <p>Ubicado en un entorno natural rodeado por un arroyo, inspirando el nombre de este oasis deportivo.</p>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre-nosotros">Sobre Nosotros</a>
        <a href="#padel">Pádel</a>
        <a href="#buffet">Buffet</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio" class="hero">
        <div>
            <h2>¡Bienvenido a Paseo del Lago!</h2>
            <p>Disfruta de partidos de pádel intensos y un buffet delicioso en un entorno moderno y deportivo, rodeado por la naturaleza.</p>
        </div>
    </section>
    <section id="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>En Paseo del Lago, ubicado en Rauch, Provincia de Buenos Aires, combinamos deporte y gastronomía en un lugar único. Nuestro nombre refleja la belleza del arroyo que nos rodea, creando un ambiente sereno y motivador para atletas de todos los niveles. Ven y vive la experiencia!</p>
    </section>
    <section id="padel">
        <h2>Complejo de Pádel</h2>
        <div class="features">
            <div class="feature">
                <h3>Canchas Profesionales</h3>
                <p>Canchas de pádel de última generación, perfectas para amateurs y profesionales.</p>
            </div>
            <div class="feature">
                <h3>Entrenamientos</h3>
                <p>Clases y entrenamientos personalizados para mejorar tu juego.</p>
            </div>
            <div class="feature">
                <h3>Torneos</h3>
                <p>Únete a nuestros torneos semanales y demuestra tus habilidades.</p>
            </div>
        </div>
    </section>
    <section id="buffet">
        <h2>Buffet Deportivo</h2>
        <div class="features">
            <div class="feature">
                <h3>Comida Saludable</h3>
                <p>Opciones nutritivas para recargar energías antes o después de jugar.</p>
            </div>
            <div class="feature">
                <h3>Variedad</h3>
                <p>Desde ensaladas frescas hasta proteínas y postres energéticos.</p>
            </div>
            <div class="feature">
                <h3>Ambiente Relajado</h3>
                <p>Disfruta de un buffet en un espacio moderno y cómodo.</p>
            </div>
        </div>
    </section>
    <footer id="contacto">
        <p>Ubicación: Rauch, Provincia de Buenos Aires</p>
        <p>Contacto: info@paseodelago.com | Tel: +123 456 7890</p>
        <p>&copy; 2023 Paseo del Lago. Todos los derechos reservados.</p>
    </footer>
</body>
</html># paseo-del-lago
