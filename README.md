<!DOCTYPE html>
<html lang="es">
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body, h1,h2,h3,h4,h5,h6 {font-family: "Montserrat", sans-serif}
.w3-row-padding img {margin-bottom: 12px}
/* Establece el ancho de la barra lateral en 120px */
.w3-sidebar {width: 120px;background: rgb(54, 54, 54);}
/* Agregue un margen izquierdo al "contenido de la página" que coincida con el ancho de la barra lateral (120 px) */
#main {margin-left: 120px}
/* Eliminar márgenes del "contenido de la página" en pantallas pequeñas */
@media only screen and (max-width: 600px) {#main {margin-left: 0}}
</style>
</head>
<body class="w3-black">
<!-- Barra de iconos (barra lateral: oculta en pantallas pequeñas) -->
<nav class="w3-sidebar w3-bar-block w3-small w3-hide-small w3-center">
  <!-- Imagen de avatar en la esquina superior izquierda -->
  <img src="view/imagnes/jayu.png" alt="Paladin Jayü" style="width:100%">
  <a href="#" class="w3-bar-item w3-button w3-padding-large w3-black">
    <i class="fa fa-home w3-xxlarge"></i>
    <p>HOGAR</p>
  </a>
  <a href="#about" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-user w3-xxlarge"></i>
    <p>ACERCA DE</p>
  </a>
  <a href="#photos" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-eye w3-xxlarge"></i>
    <p>FOTOS</p>
  </a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hover-black">
    <i class="fa fa-envelope w3-xxlarge"></i>
    <p>CONTACTO</p>
  </a>
</nav>
<!-- Barra de navegación en pantallas pequeñas (Oculta en pantallas medianas y grandes) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item w3-button" style="width:25% !important">HOME</a>
    <a href="#about" class="w3-bar-item w3-button" style="width:25% !important">ABOUT</a>
    <a href="#photos" class="w3-bar-item w3-button" style="width:25% !important">PHOTOS</a>
    <a href="#contact" class="w3-bar-item w3-button" style="width:25% !important">CONTACT</a>
  </div>
</div>
<!-- Pagina contacto -->
<div class="w3-padding-large" id="main">
  <!-- Encabezado/Inicio -->
  <header class="w3-container w3-padding-32 w3-center w3-black" id="home">
    <h1 class="w3-jumbo"><span class="w3-hide-small">Mi nombre es </span>Jayü</h1>
    <p>Gamer y coach.</p>
    <img src="view/imagnes/jayu.png" alt="boy" class="w3-image" width="992" height="1108">
  </header>
  <!-- Acerca de la sección -->
  <div class="w3-content w3-justify w3-text-grey w3-padding-64" id="about">
    <h2 class="w3-text-light-grey">Jayü</h2>
    <hr style="width:200px" class="w3-opacity">
    <p>Hola! Me llamo Jayü y soy un paladín en el mundo de World Of Warcraft. Con mi armadura brillante y mi fiel montura, recorro los vastos reinos de Azeroth, luchando contra las fuerzas del mal y ayudando a aquellos que lo necesitan. Mi experiencia en el videojuego me ha permitido adquirir habilidades y conocimientos únicos que estoy dispuesto a compartir.</p>
    <p>Ofrezco servicios y planes personalizados de entrenamiento para aquellos que deseen mejorar sus habilidades en World of Warcraft. Ya sea que estés empezando tu aventura o que seas un veterano buscando perfeccionar tus tácticas, estoy aquí para ayudarte. Mi enfoque personalizado asegura que cada sesión de entrenamiento esté adaptada a tus necesidades específicas, ayudándote a alcanzar tus objetivos en el juego. ¡Espero tener la oportunidad de guiarte en tu viaje por Azeroth!</p>
    <h3 class="w3-padding-16 w3-text-light-grey">Mis habilidades</h3>
    <p class="w3-wide">PVE (mazmorras)</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:95%"></div>
    </div>
    <p class="w3-wide">PVP (jugador contra jugador)</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:85%"></div>
    </div>
    <p class="w3-wide">Consejos y Estrategias</p>
    <div class="w3-white">
      <div class="w3-dark-grey" style="height:28px;width:90%"></div>
    </div><br>
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">230+</span><br>
        Socios
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">120+</span><br>
        Proyectos realizados
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">185+</span><br>
        Clientes felices
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge">150+</span><br>
        Reuniones
      </div>
    </div>
    <!-- Agrego un enlace a una página en raider.io -->
    <a href="https://raider.io/characters/eu/sanguino/J%C3%A4y%C3%BC" class="w3-button w3-light-grey w3-padding-large w3-section">
        <i class="fa fa-external-link"></i> Stalkear en raider.io
    </a>
    <!-- Cuadricula para tablas de precios -->
    <h3 class="w3-padding-16 w3-text-light-grey">Mis Precios</h3>
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half w3-margin-bottom">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Básica</li>
          <li class="w3-padding-16">PVE</li>
          <li class="w3-padding-16">8 días mensuales</li>
          <li class="w3-padding-16">Estrategias en PVE</li>
          <li class="w3-padding-16">PVP</li>
          <li class="w3-padding-16">3 días mensuales</li>
          <li class="w3-padding-16">Estrategias en PVP</li>
          <li class="w3-padding-16">
            <h2>10€</h2>
            <span class="w3-opacity">Al mes</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Suscríbete</button>
          </li>
        </ul>
      </div>
      <div class="w3-half">
        <ul class="w3-ul w3-white w3-center w3-opacity w3-hover-opacity-off">
          <li class="w3-dark-grey w3-xlarge w3-padding-32">Pro</li>
          <li class="w3-padding-16">PVE</li>
          <li class="w3-padding-16">13 días mensuales</li>
          <li class="w3-padding-16">Subida a 3k io</li>
          <li class="w3-padding-16">Estrategias en PVE</li>
          <li class="w3-padding-16">PVP</li>
          <li class="w3-padding-16">2.2k rating</li>
          <li class="w3-padding-16">Estrategias en PVP</li>
          <li class="w3-padding-16">
            <h2>25€</h2>
            <span class="w3-opacity">Al mes</span>
          </li>
          <li class="w3-light-grey w3-padding-24">
            <button class="w3-button w3-white w3-padding-large w3-hover-black">Suscríbete</button>
          </li>
        </ul>
      </div>
    <!-- Cuadro final/Tablas de precios -->
    </div>
    <!-- Testimonios -->
    <h3 class="w3-padding-24 w3-text-light-grey">Mi Reputación</h3>  
    <img src="view/imagnes/avatar.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Chris Fox.</span> Jugador wow.</p>
    <p>Jayü nos ayudó en una mítica +23.</p><br>
    <img src="view/imagnes/avatarchica.jpg" alt="Avatar" class="w3-left w3-circle w3-margin-right" style="width:80px">
    <p><span class="w3-large w3-margin-right">Rebecca Flex.</span> Method guild.</p>
    <p>Jayü es un compañero fiel y agradable, muy bueno en PVP.</p>
  <!-- Fin de la sección Acerca de -->
  </div>
  <!-- Sección del Portafolio -->
  <div class="w3-padding-64 w3-content" id="photos">
    <h2 class="w3-text-light-grey">Mis Personajes</h2>
    <hr style="width:200px" class="w3-opacity">
    <!-- Grid de personajes -->
    <div class="w3-row-padding" style="margin:0 -16px">
      <div class="w3-half">
        <img src="view/imagnes/jayu.png" alt="Jayü" style="width:100%">
        <img src="view/imagnes/jayumonk.png" alt="Jayü Monk" style="width:100%">
        <img src="view/imagnes/satyr.png" alt="Satyr" style="width:100%">
      </div>
      <div class="w3-half">
        <img src="view/imagnes/yoquesetio.png" alt="Yoquesetio" style="width:100%">
        <img src="view/imagnes/Montura.png" alt="Montura" style="width:100%">
        <img src="view/imagnes/Draco.png" alt="Draco" style="width:100%">
        <img src="view/imagnes/Alar.png" alt="Alar" style="width:100%">
      </div>
    <!-- Fin fotos-->
    </div>
  <!-- Sección de cartera final -->
  </div>
  <!-- Sección de Contacto -->
  <div class="w3-padding-64 w3-content w3-text-grey" id="contact">
    <h2 class="w3-text-light-grey">Contáctame</h2>
    <hr style="width:200px" class="w3-opacity">
    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Málaga, España</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Teléfono: 633942334</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: Ivansbgtattoo25@gmail.com</p>
    </div><br>
    <p>Mantengámonos en contacto. Envíame un mensaje:</p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Nombre" required name="Nombre"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Título" required name="Título"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Mensaje" required name="Mensaje"></p>
      <p>
        <button class="w3-button w3-light-grey w3-padding-large" type="submit">
          <i class="fa fa-paper-plane"></i> Enviar
        </button>
      </p>
    </form>
  <!-- Fin seccion de contacto -->
  </div>
    <!-- Footer -->
  <footer class="w3-content w3-padding-64 w3-text-grey w3-xlarge">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
    <p class="w3-medium">Todos los derechos reservados &copy; 2023 <a href="https://worldofwarcraft.blizzard.com/es-es/" target="_blank" class="w3-hover-text-green">Comprar World of Warcraft</a></p>
  <!-- Fin footer -->
  </footer>
<!-- Fin contenido pagina -->
</div>
</body>
</html>

