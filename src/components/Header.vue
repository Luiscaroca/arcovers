<template>
  <header>
    <!-- Inicio del menú -->

    <nav
      class="navbar navbar-expand-md navbar-light"
      style="
        background: linear-gradient(to right, #b20907, #131d41);
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      "
    >
      <div
        class="container-fluid"
        style="
          background: white;
          --background: linear-gradient(to right, white, white, #fbadb0);
          --border-bottom-left-radius: 0%;
          --border-top-left-radius: 0%;
          --border-bottom-right-radius: 10%;
          --border-top-right-radius: 10%;
        "
      >
        <!-- icono -->
        <a
          class="navbar-brand"
          href="/"
        >
          <img
            class="img-fluid d-inline-block align-text-top"
            alt="logo"
            src="../assets/logo.png"
            style="width: 250px; height: auto"
          />
        </a>

        <!-- boton del menu -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#menu"
          aria-controls="menu"
          aria-expanded="false"
          aria-label="toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <!-- elementos del menu colapsable -->

        <div
          class="collapse navbar-collapse"
          id="menu"
        >
          <hr class="d-md-none d-lg-block" />
          <ul class="navbar-nav mx-auto">
            <li class="nav-item">
              <!-- <a
                href="/#productos"
                class="nav-link"
              >
                Productos
              </a>
            </li>
            <li class="nav-item">
              <a
                href="/#carousel"
                class="nav-link"
              >
                Carrusel
              </a>
              </li>
            <li class="nav-item">
              <a
                href="#formacion"
                class="nav-link"
              >
                Formación
              </a>
            </li>
            <li class="nav-item">
              <a
                href="#ubicacion"
                class="nav-link"
                >Ubicación</a
              >
            </li>
            <li class="nav-item">
              <a
                href="#agendar_hora"
                class="nav-link"
                >Agendar hora</a
              >
            </li>
            <li class="nav-item">
              <a
                href="#preguntas_frecuentes"
                class="nav-link"
              >
                Preguntas frecuentes
              </a>
            </li> -->
            </li>
          </ul>

          <!-- enlaces redes sociales -->

          <hr class="d-md-none d-lg-block" />
          <hr
            class="d-none d-md-block"
            style="
              border: none;
              border-left: 1px solid hsla(200, 10%, 50%, 100);
              height: 7vh;
              width: 1px;
            "
          />
          <ul class="navbar-nav flex-row flex-wrap">
            <li class="nav-item col-5 col-md-auto p-3">
              <a
                href="https://wa.me/56942645608"
                target="_blank"
                style="color: #49c958"
              >
                <b-icon-whatsapp />
                <small class="d-md-none ms-2">WhatsApp</small></a
              >
            </li>
            <li class="nav-item col-5 col-md-auto p-3">
              <a
                href="https://www.instagram.com/a.r.covers2022/"
                target="_blank"
                style="color: #f56040"
              >
                <b-icon-instagram />
                <small class="d-md-none ms-2">Instagram</small></a
              >
            </li>
            <li class="nav-item col-5 col-md-auto p-3">
              <a
                href="https://www.mercadolibre.cl/pagina/ej20240830034654"
                target="_blank"
              >
                <img
                  src="../assets/mercadolibre_logo.png"
                  height="21px"
                  alt="Logo de Mercado Libre"
                /><small class="d-md-none ms-2">Mercado Libre</small></a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<style scoped></style>

<script></script>
