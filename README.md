<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Yelvin Smart Home</title>

<style>
body{
    margin:0;
    font-family:Arial;
    background:#0b1120;
    color:white;
}

header{
    background:#020617;
    padding:20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

header h1{
    color:#38bdf8;
    margin:0;
}

nav a{
    color:white;
    margin-left:15px;
    text-decoration:none;
}

.hero{
    padding:70px 20px;
    text-align:center;
    background:linear-gradient(to right,#0b1120,#1e293b);
}

.hero h2{
    color:#38bdf8;
    font-size:28px;
}

.btn{
    background:#25D366;
    color:white;
    padding:12px 20px;
    border-radius:5px;
    text-decoration:none;
    display:inline-block;
    margin-top:15px;
}

.section{
    padding:50px 20px;
    text-align:center;
}

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:#1e293b;
    padding:20px;
    border-radius:10px;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:10px;
}

.gallery img{
    width:100%;
    border-radius:10px;
}

.highlight{
    background:#020617;
    padding:40px;
}

.contact{
    background:#1e293b;
    padding:30px;
    border-radius:10px;
    max-width:400px;
    margin:auto;
}

.footer{
    background:#020617;
    text-align:center;
    padding:20px;
    margin-top:20px;
}

/* WhatsApp flotante */
.whatsapp{
    position:fixed;
    bottom:20px;
    right:20px;
    background:#25D366;
    padding:15px;
    border-radius:50%;
    text-decoration:none;
    color:white;
    font-size:20px;
}
</style>
</head>

<body>

<header>
    <h1>Yelvin Smart Home</h1>
    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#trabajos">Trabajos</a>
        <a href="#contacto">Contacto</a>
    </nav>
</header>

<section class="hero">
    <h2>Soluciones inteligentes para tu hogar</h2>
    <p>Seguridad, automatización y energía solar con instalación profesional</p>
    <a href="https://wa.me/16175951216" class="btn">📲 Cotizar ahora</a>
</section>

<section class="section" id="servicios">
    <h2>Nuestros Servicios</h2>

    <div class="services">
        <div class="card">
            <h3>📷 Cámaras de Seguridad</h3>
            <p>Monitoreo 24/7 desde tu celular</p>
        </div>

        <div class="card">
            <h3>🏠 Automatización</h3>
            <p>Control inteligente de tu hogar</p>
        </div>

        <div class="card">
            <h3>❄️ Aire Acondicionado</h3>
            <p>Instalación y reparación</p>
        </div>

        <div class="card">
            <h3>☀️ Paneles Solares</h3>
            <p>Ahorra energía y dinero</p>
        </div>
    </div>
</section>

<section class="section" id="trabajos">
    <h2>Trabajos Realizados</h2>

    <div class="gallery">
        <img src="https://via.placeholder.com/300" alt="">
        <img src="https://via.placeholder.com/300" alt="">
        <img src="https://via.placeholder.com/300" alt="">
        <img src="https://via.placeholder.com/300" alt="">
    </div>

    <p>(Aquí luego ponemos fotos reales tuyas)</p>
</section>

<section class="highlight">
    <h2>¿Por qué elegirnos?</h2>
    <p>✔ Trabajo garantizado</p>
    <p>✔ Atención rápida</p>
    <p>✔ Experiencia profesional</p>
    <p>✔ Precios competitivos</p>
</section>

<section class="section" id="contacto">
    <h2>Contáctanos</h2>

    <div class="contact">
        <p>📞 617-595-1216</p>
        <p>📧 yerbinadonis@gmail.com</p>

        <a href="https://wa.me/16175951216" class="btn">Hablar por WhatsApp</a>
    </div>
</section>

<div class="footer">
    <p>© 2026 Yelvin Smart Home</p>
</div>

<a href="https://wa.me/16175951216" class="whatsapp">💬</a>

</body>
</html>
