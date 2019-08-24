<template>
  <div class="profile-page">
    <section class="section-profile-cover section-shaped my-0">
      <div class="shape shape-style-1 shape-primary shape-skew alpha-4">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        <span></span>
      </div>
    </section>
    <section class="section section-skew" style="margin-top: -180px;">
      <div class="container">
        <card shadow class="card-profile mt--300" no-body>
          <div class="px-4">
            <div class="row justify-content-center">
              <div class="col-lg-3 order-lg-2">
                <div class="card-profile-image">
                  <a href="#">
                    <img src="@/assets/arduino-led.jpg" class="rounded-circle" />
                  </a>
                </div>
              </div>
              <div class="col-lg-4 order-lg-3 text-lg-right align-self-lg-center">
                <div class="card-profile-actions py-4 mt-lg-0">
                  <base-button type="danger" size="sm" class="mr-4">Arduino</base-button>
                  <base-button type="success" size="sm" class="float-right">Lenguaje C</base-button>
                </div>
              </div>
              <div class="col-lg-4 order-lg-1">
                <div class="card-profile-stats d-flex justify-content-center">
                  <div>
                    <span class="heading fixHeading">26/09/2019</span>
                    <span class="description">Fecha de inicio</span>
                  </div>
                  <div>
                    <span class="heading fixHeading">Principiante</span>
                    <span class="description">Nivel</span>
                  </div>
                  <!-- <div>
                    <span class="heading fixHeading">10</span>
                    <span class="description">Clases</span>
                  </div> -->
                </div>
              </div>
            </div>
            <div class="text-center mt-5">
              <h3>
                Introducción a la Robótica
                <!-- <span class="font-weight-light">, 27</span> -->
              </h3>
              <!-- <div class="mt-4"> -->
              <div class="h6 font-weight-300">
                <p>Aprendé los concéptos básicos de la programación y la electrónica mediante al uso de la plataforma de desarrollo más popular de la actualidad: Arduino.</p>
              </div>
              <!-- <div class="mt-4">
                <strong>Lugar</strong> Beccar, San Isidro
              </div>
              <div>
                <strong>Horario</strong> Jueves 17 a 20 Hrs (10 clases)
              </div>
              <div>
                <strong>Fecha de inicio</strong> 26 de Septiembre 2019
              </div>
              <div >
                <strong>Fecha de finalización</strong> 28 de Noviembre 2019
              </div>
              <div>
                <strong>Precio</strong> $10500 (consultar por formas de pago)
              </div> -->
            </div>
            <div class="mb-5 text-center">
              <div class="row justify-content-center">
                <div class="col-lg-9">
                  <tabs-curso01></tabs-curso01>
                  <base-button @click="window.location.href = '/#contactanos'" type="success" class="mt-4">Estoy interesado</base-button>
                </div>
              </div>
            </div>
          </div>
        </card>
      </div>
    </section>
  </div>
</template>
<script>
import TabsCurso01 from "@/views/components/JavascriptComponents/TabsCurso01";

export default {
  components: { TabsCurso01 }
};
</script>
<style>
.fixHeading {
    font-size: 1rem !important;
}
</style>
