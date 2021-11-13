# squad-6
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">



  <link href="/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href=/css/estilos.css>
  <title>MechanicToCar</title>
</head>
<body>


<header>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HEALTHY MOTORS</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Inicio</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Sobre nosotros</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Mas informacion</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Comentarios</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Contactanos</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Descargar
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Play Store</a></li>
              <li><a class="dropdown-item" href="#">App Store</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Something else here</a></li>
            </ul>
          </li>

        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="Buscar" placeholder="Buscar" aria-label="Buscar">
          <button class="btn btn-outline-success" type="submit">Buscar</button>
        </form>
      </div>
    </div>
  </nav>
</header>


<main>

    <section class="container pt-xxl-5 " >
      <div class="card text-white bg-dark mb-3" style="max-width: 27rem;">
        <div class="card-header">MECHANIC TO CAR</div>
        <div class="card-body">
          <h5 class="card-title">Solicita cualquier mecanico en cualquier lugar donde estes
            desde tu celular</h5><br>
        </div>
        <div class="container pt-0">
          <img src= img/celular.png class="imagen-celu" alt="">
        </div>
      </div>
      <div class="card text-white bg-dark mb-3" style="max-width: 27rem;">
        <h4>Registrese</h4>
        <label for="nombres"></label><input class="controls" type="text" name="nombres" id="nombres" placeholder="Ingrese sus nombres">
        <label for="apellidos"></label><input class="controls" type="text" name="nombres" id="apellidos" placeholder="Ingrese sus apellidos">
        <label for="correo"></label><input class="controls" type="email" name="nombres" id="correo" placeholder="Ingrese su correo">
        <label for="contraseña"></label><input class="controls" type="password" name="nombres" id="contraseña" placeholder="Ingrese su contraseña">
        <input class="botons" type="submit" value="Registrar">
      </div>
    </section>


  <section class="contenedor ">
    <h2 class="titulo">Sobre Nosotros</h2>
    <div class="contendor-sobre-nosotros">
      <img src= img/SobreNosotros.jpg class="imagen-about-us" alt="">
      <div class="contenido-textos">
        <h3><span>1</span> Objectivos</h3>
        <p>Nuestra empresa Healthy Motors tiene como objetivo principal
          brindar soluciones rápidas a sus clientes, por ello realizamos un
          aplicativo llamado MechanicToCar.</p>
        <h3><span>2</span>Siempre atento a las necesidades</h3>
        <p> Muchas personas que cuentan con vehículo muchas
          veces se han quedado varados en medio del camino o simplemente
          no hay podido salir de su casa porque su auto necesita revisión de
          una persona adecuada.</p>

      </div>
    </div>
  </section>

  <section class="caracteristicas">
    <div class="container">
      <h2 class="titulo">Siempre a tu lado</h2>
      <div class="galeria-info">

        <div class="imagen-info">
          <img src="img/tiempo.jpg" alt="">
          <div class="hover-galeria">
            <p>En cualquier momento y lugar</p>
          </div>
        </div>

        <div class="imagen-info">
          <img src="img/casa.jpg" alt="">
          <div class="hover-galeria">
            <p>
              Solicitalo desde la comodidad
              de tu hogar
            </p>
          </div>
        </div>

        <div class="imagen-info">
          <img src="img/movil.jpg" alt="">
          <div class="hover-galeria">
            <p>
              Llevala contigo a todos lados
              en tu celular
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <div class="descarga">
    <h2 class="titulo">Descargar</h2>
    <div class="cards">
      <div class="card1">
        <img src="img/CelularM.png" alt="">
      </div>
      <div class="card">
        <img src="img/Apple.png" alt="">
        <div class="contenido-texto-card">
          <h4>Disponible en AppStore</h4>
          <p>Para descargarlo haz click aqui</p>
        </div>
      </div>
      <div class="card">
        <img src="img/PlayStore.png" alt="">
        <div class="contenido-texto-card">
          <h4>Disponible en la Play Store</h4>
          <p>Para descargarlo haz click aqui</p>
        </div>
      </div>
    </div>
  </div>

  <section class="comentarios">
    <div class="container">
      <h2 class="titulo">Comentarios</h2>
      <div class="comentarios-cont">
        <div class="comentarios-ind">
          <img src="img/cliente1.jpg" alt="">
          <h3>Rodrigo</h3>
          <p>Gracias a esta aplicacion, pude contactar a un mecanico
            cuando mas lo necesite.
          </p>
        </div>
        <div class="comentarios-ind">
          <img src="img/cliente2.jpg" alt="">
          <h3>Lucas</h3>
          <p>Antes no encontraba productos que necesita para mi
            vehiculo. Una vez que lo descargue encuentro facilmente
            lo que necesito y a un precio accesible.
          </p>
        </div>
        <div class="comentarios-ind">
          <img src="img/cliente3.jpg" alt="">
          <h3>Juan</h3>
          <p>Estube por un periodo muy corto sin clientes.
            Desde que escuche sobre esta aplicacion ahora mi negocio
            le va mejor que nunca.</p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container-footer">
      <section class="form-consultas">
        <h4>Consultas</h4>
        <label for="correos"></label><input class="controls" type="email" name="nombres" id="correos" placeholder="Ingrese su correo">
        <label for="consulta"></label><input class="controls2" id="consulta" name="nombres" placeholder="Escriba su consulta">
        <input class="Enviar" type="submit" value="Enviar consulta">
      </section>
      <div class="content-foo">
        <img src="img/Facebook.png" alt="">
      </div>
      <div class="content-foo">
        <img src="img/Insta.png" alt="">
      </div>
      <div class="content-foo">
        <img src="img/Whats.png" alt="">
      </div>
    </div>
  </footer>

</main>
<script src="/js/bootstrap.bundle.min.js"></script>
</body>
</html>
