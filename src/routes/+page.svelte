<script>

</script>

<main>
  <div class="container">
    <div id="uno" class="card mb-3" style="max-width: 800px;">
      <div class="row g-0">
        <div class="col-md-4">
          <img src="/img/imgVideojuegos.png" class="img-fluid rounded-start" alt="img_CursoVideojuegos">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Desarrollo de Videojuegos y Realidad Virtual</h5>
            <p class="card-text">
              El desarrollo de videojuegos es el proceso de creación de un videojuego, desde el concepto inicial hasta el videojuego en su versión final. </p>
            <button class="btn btn-primary"><a class="text-white" href="/videojuegos">Leer más...</a></button>
          </div>
        </div>
      </div>
    </div>
    <br>
    <br>
    <div id="dos" class="card mb-3" style="max-width: 800px;">
      <div class="row g-0">
        <div class="col-md-4">
          <img src="/img/imgCiberseguridad.jpg" class="img-fluid rounded-start" alt="img_CursoCiberseguridad" height="150px">
        </div>
        <div class="col-md-8">
          <div class="card-body">
            <h5 class="card-title">Curso de Ciberseguridad</h5>
            <p class="card-text">La ciberseguridad es la práctica de defender los ordenadores, los servidores, los dispositivos móviles, los sistemas electrónicos, las redes y los datos de ataques maliciosos. También se conoce como seguridad de tecnología de la información</p>
            <button class="btn btn-primary"><a class="text-white" href="/ciberseguridad">Leer más...</a></button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <br>
</main>

<style>
  main{
    padding-top: 3rem;
  }

  #uno{
    animation-name: lateral;
    animation-duration: .8s;
  }

  #dos{
    animation-name: lateral;
    animation-duration: 1.5s;
  }

  @keyframes lateral {
    0%{
      margin-left: 100%;
    }
    100%{
      margin-left: 0%;
    }
  }

  .text-white{
      text-decoration: none;
  }

  .card{
    transition: transform .6s;
  }

  .card:hover{
    transform: scale(1.1); 
  }
</style>
