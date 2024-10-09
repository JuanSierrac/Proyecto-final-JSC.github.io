<!DOCTYPE html>
<html lang="esp">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProyJCA</title>
   <script src="scrip.js"></script>
   <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main>
    <nav class="nav_container">
        <div class="container">
            <div class="logo">
                <img src="https://i.pinimg.com/736x/79/6c/4f/796c4fedf73c0e9ed63727ac402b235b.jpg" alt="Logo de benditos fritos ">
                <span>BENDITOS FRITOS</span>
            </div>
      <div class="cont">
          <ul>
              <li><a href="#inicio">Inicio</a></li>
              <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
              <li><a href="#servicios">Servicios</a></li>
              <li><a href="#reseñas">Reseñas</a></li>
              <li><a href="#contacto">Contacto</a></li>
              <li><a href="JSC/registro.html" id="RegisterLink">Registrarse</a></li>
              <li><a href="JSC/login.html">Iniciar Sesión</a></li>
          </ul>
      </div>
  </nav>

  <header class="banner" id="inicio">
    <div class="main">
        <h1>Benditos Fritos</h1>
        <p>Deleitate con nuestros deliciosos fritos tipicos.</p>
    </div>
</header>


    <section class="about" id="sobre-nosotros">
      <div class="container">
          <div class="about-content">
              <div class="about-text">
                  <h2>Sobre Nosotros</h2>
                  <p>Somos un negocio orientado a la realización de fritos tipicos de la ciudad de cartagena, tenemos formas y sabores nuevos e innvovadores.</p>
              </div>
              <div class="about-image">
                  <img src="https://th.bing.com/th/id/OIP.c8B7IsumAjE3dKsnlc5GHAHaE7?rs=1&pid=ImgDetMain" alt="Dedos de quesos fritos" >
              </div>
          </div>
      </div>
  </section>

  <!-- Sección de servicios -->
  <section class="services" id="servicios">
      <div class="container">
          <h2 >Los diversos fritos que ofrecemos: </h2>
          <h3>CLÁSICOS</h3>
          <div class="service-grid">
              <div class="service-card" for="item">
                  <h3>Deditos</h3>
                  <ul class="item">
                    <li>Queso</li>
                    <li>Salchicha</li>
                    <li>Bocadillo</li>
                  </ul>
                  <p><strong>20 UND</strong></p>
                  <p><strong>CONGELADOS $13.000</strong></p>
              </div>
              <div class="service-card" for="item">
                  <h3>Empanadas</h3>
                  <ul class="item" name="item">
                    <li>Carne</li>
                    <li>Pollo</li>
                    <li>Hawaiiana</li>
                    <li>Espinaca con queso</li>
                  </ul>
                  <p><strong>12 UND</strong></p>
                  <p><strong>CONGELADOS $13.000 </strong></p>
              </div>
              <div class="service-card" for="item">
                  <h3>Otros</h3>
                  <ul class="item" name="item">
                    <li>Rollitos de Salchicha</li>
                  </ul>
                  <p><strong>24 UND</strong></p>
                  <p><strong>CONGELADOS $13.000</strong></p>
              </div>
          </div>
      </div>
  
    <div class="container">
        <h2>Los diversos fritos que ofrecemos: </h2>
        <h3>TÍPICOS</h3>
        <div class="service-grid">
            <div class="service-card">
                <h3>Empanadas </h3>
                <ul class="item">
                    <li>Carne</li>
                    <li>Pollo</li>
                    <li>Ranchera</li>
                </ul>
                <p><strong>6 UND</strong></p>
                <p><strong>FRITOS $13.000</strong></p>
            </div>
            <div class="service-card">
                <h3>Arepas </h3>
                <ul class="item">
                <li>Carne y queso</li>
                <li>Pollo y queso</li>
                <li>Huevo y carne </li>
                <li>Huevo y pollo</li>
                <li>Huevo y mariscos</li>
                <li>Arepa dulce</li>
                <li>Arepa trifásica</li>
               </ul>
                <p><strong>6 UND</strong></p>
                <p><strong>FRITOS $25.000 </strong></p>
            </div>
            <div class="service-card">
                <h3>Otros</h3>
                <ul class="item">
                    <li>Carimañola</li>
                    <li>Buñuelos</li>
                    <li>Papa rellena</li>
                </ul>
                <p><strong>6 UND</strong></p>
                <p><strong>FRITOS $13.000</strong></p>
            </div>
        </div>
    </div>
</section>

<!-- Sección de reseñas de clientes -->
<section class="reviews" id="reseñas">
    <div class="container">
        <h2>Lo que dicen nuestros clientes: </h2>
        <div class="review-grid">
            <div class="review-card">
                <div class="review-header">
                    <img src="https://static.vecteezy.com/system/resources/previews/019/879/186/large_2x/user-icon-on-transparent-background-free-png.png"  alt="María González" >
                    <div>
                        <h3>María González</h3>
                    </div>
                </div>
                <p>"Los mejores fritos que he probado de verdad hacen alusión a su nombre, son benditos."</p>
            </div>
            <div class="review-card">
                <div class="review-header">
                    <img src="https://static.vecteezy.com/system/resources/previews/019/879/186/large_2x/user-icon-on-transparent-background-free-png.png" alt="Carlos Rodríguez">
                    <div>
                        <h3>Carlos Rodríguez</h3>
                    </div>
                </div>
                <p>"Son muy buenos y muy deliciosos, estamos muy satisfechos con ellos. ¡Super Recomendados!"</p>
            </div> 
        </div>
    </div>
</section>

  <!-- Pie de página con enlaces a redes sociales -->
  <footer id="contacto">
      <div class="container">
          <h2>Síguenos en redes sociales</h2>
          <div class="social-links">
              <a href="https://www.instagram.com/benditos_fritos/" target="_blank">Benditos_Fritos</a>
              <a href="https://www.facebook.com/profile.php?id=61561346353978" target="_blank">Facebook</a>
              <a href="#" target="_blank">Whatsapp-324 5016765</a>
          </div>
      </div>
  </footer>
</body>
</html>
