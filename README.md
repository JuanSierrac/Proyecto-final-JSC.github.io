<!DOCTYPE html>
<html lang="esp">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ProyJCA</title>
   <script src="scrip.js"></script>
   <link rel="stylesheet" href="styles.css">
<styles>
body, html{
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #000000;
}

.main{
    padding: 50px; 
    width: 70%;
    margin: auto;
    overflow: hidden;
    font-family: monospace;
    font-size: 1.50rem;
    background-image: url("https://i.pinimg.com/736x/1a/e9/94/1ae994a53caff1cbbdb369037a1f1d39.jpg");
    background-repeat: no-repeat;
    background-size: cover;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
    color: #000000;
}


/* Menú de navegación */
nav {
    background-color: #c6af91;
    color: #fff;
    padding: 1rem 0;
}

.logo {
    display: flex;
    align-items: center;
}

img{
    border-radius: 50%;
    width: 80px;
    height: auto;
}

.logo span {
    font-size: 1.5rem;
    font-weight: bolder; 
    padding: 1rem;
}

.nav_container {
    align-items: center;
    padding: 1rem 0;
    background: linear-gradient(#632715, #bab236, #6c4b11);
    margin: auto;
    overflow: hidden;
    display: flex;
    justify-content: space-around;
    font-size: 1.0rem;
    font-family: cursive;
}

nav .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    display: flex;
    list-style: none;
}
nav ul li {
    margin-left: 1rem;
}

nav a {
    color: #000000;
    text-decoration: none;
    padding: 0.5rem;
    font-size: 1.25rem;
}

/* Banner */

.banner{
    color: #000000;
    text-align: center;
    padding: auto;
}

.banner h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.banner p {
    font-size: 1.2rem;
    margin-bottom: 1rem;
}

/* Secciones */

section {
    padding: 4rem 0;
}

.about {
    background-color: #000000;
    text-align: center;
    font-family: serif;
    font-size: 1.5rem;
}

.about-content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: rgb(255, 255, 255);
}

.about-text {
    flex: 1;
    padding-right: 2rem;
    border-bottom: 3px solid #3b3b4f;
}

.about-image {
    flex: 1;
}

.about-image img {
   width: 80%;
   height: auto;
   border-radius: 10px;
   margin-left: 100px;
}

/* Servicios */

.services{
    background-color: burlywood;
    text-align: center;
    background-image: url("https://i.pinimg.com/736x/0c/ca/91/0cca91bcf896e937b2117b1e2e5ce29b.jpg");
    background-repeat: no-repeat;
    background-size: cover  ;
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.service-card {
    background-color: #f4f4f4;
    padding: 1.5rem;
    border-radius: 10px;
    text-align: center;
}

.item{
    text-align: center;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    padding: 10%;
}

/* Reseñas */
.reviews {
    background-color: #f4f4f4;
    text-align: center;
}
.review-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}
.review-card {
    background-color: #fff;
    padding: 1.5rem;
    border-radius: 10px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.review-header {
    display: flex;
    align-items: center;
    margin-bottom: 1rem;
}

.review-header img {
    width: 80px;
    height: auto;
    border-radius: 50%;
    margin-right: 1rem;
}

/* Pie de página */
footer {
    background: linear-gradient(#632715, #bab236, #6c4b11);
    color: #fff;
    text-align: center;
    padding: auto;
    font-size: 14px;
    
}

  .social-links a {
    margin-bottom: 5px;
    color: #000000;
    font-size: 1.5rem;
    padding: 10px;
  }
  
  a {
    color: black;
  }
  
  a:visited {
    color: black;
  }
  
  a:hover {
    color: brown;
  }
  
  a:active {
    color: brown;
  }

/* Responsive */
@media (max-width: 768px) {
    .container {
        width: 90%;
    }
    nav .container {
        flex-direction: column;
    }
    nav ul {
        margin-top: 1rem;
    }
    .about-content {
        flex-direction: column;
    }
    .about-text {
        padding-right: 0;
        margin-bottom: 2rem;
    }
}
</styles>
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
