<template>
  <footer>
    <div class="container">
      <div class="row justify-content-between w-100">
        <div class="col-md-4">
          <div class="footer-brand">
            <div>
              <img
                src="../assets/logo.png"
                alt="LOGO"
              />
            </div>
            <h4>Redes sociales:</h4>
            <div class="mb-4 mb-md-0">
              <ul class="navbar-nav flex-row justify-content-center w-50">
                <li class="nav-item col-1 col-md-auto">
                  <a
                    class="h4"
                    href="https://wa.me/56942645608"
                    target="_blank"
                    style="color: #49c958"
                  >
                    <b-icon-whatsapp />
                  </a>
                </li>
                <li class="nav-item col-1 col-md-auto">
                  <a
                    class="h4"
                    href="https://www.instagram.com/a.r.covers2022/"
                    target="_blank"
                    style="color: #f56040"
                  >
                    <b-icon-instagram
                  /></a>
                </li>
                <li
                  class="nav-item col-5 col-md-auto d-flex align-items-center"
                >
                  <a
                    href="https://www.mercadolibre.cl/pagina/ej20240830034654"
                    target="_blank"
                  >
                    <img
                      src="../assets/mercadolibre_logo.png"
                      height="21px"
                      style="width: auto"
                      alt="Logo de Mercado Libre"
                  /></a>
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-md-5">
          <div>
            <div>
              <h4>Información de contacto</h4>
            </div>
            <ul>
              <li><strong>Teléfono: </strong>+56 9 4264 5608</li>
              <li><strong>Correo: </strong>#####@gmail.com</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
    <div class="container text-light text-center">
      <small class="text-black-50">&copy;Luis Caroca, {{ currentDate }}</small>
    </div>
  </footer>
</template>

<style scoped>
footer {
  border-top: 8px solid transparent;
  border-image: linear-gradient(to right, #b20907, #131d41);
  border-image-slice: 1;
  padding: 25px;
  box-shadow: 0px 4px 30px rgba(0, 0, 0, 0.2);
  background-color: rgb(245, 245, 245);
}
.footer-brand img {
  width: 50%;
}
ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

.activo {
  text-decoration: underline;
}
</style>

<script>
export default {
  data() {
    return {
      currentDate: new Date().getFullYear(),
    };
  },
  mounted() {
    // Actualiza constantemente el año para modificarla si es necesario
    setInterval(() => {
      this.currentDate = new Date().getFullYear();
    }, 1000);
  },
};
</script>
