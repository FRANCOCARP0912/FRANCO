<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Inicio</title>
    <link rel="stylesheet" type="text/css" href="C:\Users\PC02\Desktop\Nueva carpeta\.css"
</head>
<body>
    <header>
        <h1>Sistema de Monitoreo de Gas</h1>
        <nav>
            <ul>
                <li><a href="inicio.html" class="active">Inicio</a></li>
                <li><a href="portada.html">Portada</a></li>
                <li><a href="contacto.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="descripcion">
            <h2>¿Qué es un Sistema de Monitoreo de Gas?</h2>
            <p>Un sistema de monitoreo de gas es un sistema que detecta a tiempo gases combustibles, inflamables y tóxicos, y hace sonar una alarma cuando los niveles de estos gases superan los límites de exposición ocupacional. Estos sistemas pueden ser fijos o portátiles, lo que los hace versátiles para diferentes entornos.</p>
        </section>
        <section class="beneficios">
            <h2>Beneficios del Monitoreo de Gas</h2>
            <p>El monitoreo de gas ofrece varias ventajas clave:</p>
            <p>Permite responder más rápido durante emergencias, reducir procesos manuales y detectar patrones en incidentes de seguridad. Además, ayuda a disminuir riesgos de manera proactiva, mejorando la seguridad general en el lugar de trabajo.</p>
        </section>
        <section class="caracteristicas">
            <h2>Características del Sistema</h2>
            <p>Nuestros sistemas de monitoreo están diseñados para ofrecer una supervisión completa y control remoto de parámetros operativos como presiones, temperaturas y caudales. Además, incluyen opciones de alimentación y transmisión configurables, lo que los hace altamente personalizables.</p>
            <p>Estos sistemas pueden monitorear desde disyuntores aislados de gas hasta sistemas de distribución de gas más grandes, integrando monitores de densidad de gas SF6 y otros componentes en una sola plataforma. Funcionan extrayendo una muestra representativa del flujo de gases para asegurar datos precisos.</p>
        </section>
        /* Estilos Generales */
body {
    font-family: 'Lato', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #333; /* Fondo oscuro */
}

/* Encabezado */
header {
    background-color: #444; /* Fondo gris oscuro */
    color: #fff;
    padding: 15px; /* Padding moderado */
    text-align: center;
    border-bottom: 2px solid #555; /* Borde inferior gris oscuro */
    box-shadow: 0 2px 4px rgba(0,0,0,0.5); /* Sombra oscura */
}

header h1 {
    margin: 0;
    font-size: 22px; /* Tamaño de fuente moderado */
    font-weight: bold; /* Fuente más fuerte */
    letter-spacing: 1px; /* Espaciado entre letras */
    border-bottom: 1px solid #555; /* Marco inferior gris oscuro */
}

/* Navegación */
nav {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 0 10px; /* Padding lateral */
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
}

nav ul li {
    margin-right: 15px; /* Espacio entre elementos */
}

nav a {
    color: #ccc; /* Gris claro */
    text-decoration: none;
    transition: color 0.2s ease;
    font-size: 16px; /* Tamaño de fuente moderado */
    padding: 5px 10px; /* Padding para los enlaces */
    border-radius: 5px; /* Esquinas redondeadas */
}

nav a:hover {
    background-color: #555; /* Fondo gris oscuro al pasar el mouse */
    color: #fff; /* Blanco al pasar el mouse */
}

nav a.active {
    background-color: #666; /* Gris más oscuro al activar */
    color: #fff; /* Blanco al activar */
    border-radius: 5px; /* Esquinas redondeadas */
}

/* Contenido Principal */
main {
    display: flex;
    justify-content: center;
    padding: 40px 20px; /* Padding moderado */
    flex-direction: column;
}

/* Secciones */
section {
    background-color: #444; /* Fondo gris oscuro */
    padding: 20px; /* Padding moderado */
    border: 1px solid #555; /* Marco gris oscuro */
    border-radius: 10px; /* Esquinas redondeadas */
    box-shadow: 0 0 10px rgba(0,0,0,0.5); /* Sombra oscura */
    max-width: 800px;
    margin: 20px auto; /* Espacio entre secciones */
    text-align: center;
    color: #fff; /* Texto blanco */
}

/* Formulario de Contacto */
.contacto {
    background-color: #444; /* Fondo gris oscuro */
    padding: 20px; /* Padding moderado */
    border: 1px solid #555; /* Marco gris oscuro */
    border-radius: 10px; /* Esquinas redondeadas */
    box-shadow: 0 0 10px rgba(0,0,0,0.5); /* Sombra oscura */
    max-width: 600px;
    margin: 20px auto; /* Espacio entre secciones */
}

.campo-formulario {
    margin-bottom: 20px; /* Espacio entre campos */
    text-align: left;
    color: #fff; /* Texto blanco */
}

.campo-formulario label {
    display: block;
    margin-bottom: 10px;
}

.campo-formulario input, .campo-formulario textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #555; /* Marco gris oscuro */
    border-radius: 5px; /* Esquinas redondeadas */
    background-color: #333; /* Fondo oscuro */
    color: #fff; /* Texto blanco */
}

.btn-enviar {
    background-color: #555; /* Gris oscuro */
    color: #fff;
    padding: 10px 20px;
    border: none;
    border-radius: 5px; /* Esquinas redondeadas */
    cursor: pointer;
    transition: background-color 0.2s ease;
}

.btn-enviar:hover {
    background-color: #666; /* Gris más oscuro al pasar el mouse */
}

/* Pie de Página */
footer {
    background-color: #444; /* Fondo gris oscuro */
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
    </main>
    <footer>
        <p>&copy; 2025 FRANCO COTAL</p>
    </footer>
</body>
</html>
