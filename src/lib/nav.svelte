<script>
</script>

<main class="sticky-top">
  <header class="animated menu-fixed-out ">
    <div class="container">
      <nav class="navbar navbar-expand-xxl">
        <div class="container-fluid">
          <a id="logo-a" href="/"><img id="logo" src="img/logoIes.png" alt="Logo IesAzarquiel"/></a>
          <button
            class="navbar-toggler"
            type="button"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
            data-bs-toggle="offcanvas" 
            data-bs-target="#demo"
          >
            <i class="fa-solid fa-bars"/>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#!">INICIO</a>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  AL DÍA
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Action</a></li>
                  <li><a class="dropdown-item" href="#!">Another action</a></li>
                  <li><hr class="dropdown-divider" /></li>
                  <li>
                    <a class="dropdown-item" href="#!">Something else here</a>
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#!">EL LORO</a>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  EL CENTRO
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Action</a></li>
                  <li><a class="dropdown-item" href="#!">Another action</a></li>
                  <li><a class="dropdown-item" href="#!">Something else here</a></li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  SECRETARÍA
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Action</a></li>
                  <li><a class="dropdown-item" href="#!">Another action</a></li>
                  <li><hr class="dropdown-divider" /></li>
                  <li>
                    <a class="dropdown-item" href="#!">Something else here</a>
                  </li>
                </ul>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#!"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  FAMILIAS
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#!">Familias en red</a></li>
                  <li>
                    <a class="dropdown-item" href="#!"
                      >Activar SMS Faltas Asistencia</a
                    >
                  </li>
                  <li><a class="dropdown-item" href="#!">Calendario Escolar</a></li>
                  <li>
                    <a class="dropdown-item" href="#!"
                      >Estructura Académica 4º<br />ESO LOMCE</a
                    >
                  </li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#!">BOLSA</a>
              </li>
            </ul>
            <div class="d-flex">
              <i data-bs-toggle="offcanvas" data-bs-target="#demo" id="menu" class="fa-solid fa-bars"></i>
            </div>
          </div>
        </div>
      </nav>
    </div>
  </header>

  <!-- Offcanvas Sidebar -->
  <div class="offcanvas offcanvas-end text-bg-dark" id="demo">
    <div class="offcanvas-header">
      <h1 class="offcanvas-title">
        Search
      </h1>
      <button type="button" class="btn-close btn-close-white text-reset" data-bs-dismiss="offcanvas"></button>
    </div>
    <div class="offcanvas-body">
      <p><input type="search" placeholder="Search ..." name="buscador"/></p>
      <p><i class="fa-solid fa-caret-down"/> INICIO</p>
      <p><i class="fa-solid fa-caret-down"/> AL DÍA</p>
      <p><i class="fa-solid fa-caret-down"/> EL LORO</p>
      <p><i class="fa-solid fa-caret-down"/> SECRETARÍA</p>
      <p><i class="fa-solid fa-caret-down"/> FAMILIAS</p>
      <p><i class="fa-solid fa-caret-down"/> BOLSA</p>
    </div>
  </div>
</main>

<style lang="sass">
  main
    font-family: 'Open Sans', sans-serif
    background-color: white

    header
      box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 15px
      height: 5.5rem
      display: flex
      align-items: center

    #logo
      height: 3.3rem
      margin-left: 3.5rem

    .container-fluid
      button
        border: none

        &:hover
          color: #89D5F2
          transition: 400ms
      a
        color: gray
        font-weight: lighter
        letter-spacing: 1px
        font-size: 0.75rem
        &:hover
          color:#89D5F2


    .navbar-collapse
      margin-left: 13rem


    #menu
      cursor: pointer
      font-size: 1.5rem
      margin-left: -7rem
      &:hover
        color: #89D5F2
        transition: 400ms


    @media (max-width: 600px)
      #logo
        height: 3.8rem
        width: 15rem
        margin-left: 0
    

    .offcanvas
      width: 21.2rem
      
    .offcanvas-body
      input
        height: 2.2rem
        border-radius: 0.3rem
        background-color: transparent
        border: 1px solid gray
        color: white
      p
        transition: .5s
        &:hover
          background-color: #1c1c1c
          border-radius: 8px
          cursor: pointer
      i
        padding: 0.5rem
</style>
