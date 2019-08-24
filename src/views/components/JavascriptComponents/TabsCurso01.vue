<template>
  <div class="row justify-content-center">
    <div class="col-lg-12">
      <!-- Tabs with icons -->
      <tabs fill class="flex-column flex-md-row">
        <card shadow slot-scope="{activeTabIndex}">
          <tab-pane key="tab1">
            <template slot="title">
              <i class="ni ni-calendar-grid-58 mr-2"></i>Información
            </template>

            <div class="description">
              <strong>Lugar</strong> Beccar, San Isidro
            </div>
            <div class="description">
              <strong>Horario</strong> Jueves 17 a 20 Hrs (10 clases)
            </div>
            <div class="description">
              <strong>Fecha de inicio</strong> 26 de Septiembre 2019
            </div>
            <div class="description">
              <strong>Fecha de finalización</strong> 28 de Noviembre 2019
            </div>
            <div class="description">
              <strong>Precio</strong> $10500 (consultar por formas de pago)
            </div>
          </tab-pane>

          <tab-pane key="tab2">
            <template slot="title">
              <i class="ni ni-books mr-2"></i>Requisitos/Materiales
            </template>
            <div class="description">
              <strong>Requisitos</strong>
              <br />No se requiere experiencia previa de ningún tipo, te vamos a enseñar todo lo necesario.
              <br />Lo único que necesitas es una notebook/laptop para poder trabajar comodamente (en caso de no contar con una consultar por privado).
            </div>
            <div class="description" style="padding-top: 10px;">
              <strong>Materiales</strong>
              <br />Al comenzar el curso se entrega un kit de materiales que incluye un Arduino y todos los componentes necesarios para completar el curso. El kit es tuyo para que lo aproveches al máximo tanto durante el curso como depués!
            </div>
          </tab-pane>

          <tab-pane key="tab3">
            <template slot="title">
              <i class="ni ni-single-copy-04 mr-2"></i>Temario
            </template>

            <p
              class="description"
            >Próximamente vas a encontrar el programa del curso en esta sección.</p>

            <p class="description">
              El curso tiene los siguientes objetivos:
              <br />+ Introducción al lenguaje Arduino y a los componentes electrónicos.
              <br />+ Armado de circuitos básicos, conocimiento de sensores y comunicación con sistemas informaticos.
              <br />+ Enfoque en profundidad en diversas aplicaciones comunes en el area de la robótica experimental.
              <br />+ Desarrollar un proyecto que integre los conocimientos adquiridos en el curso.
            </p>
          </tab-pane>
        </card>
      </tabs>
    </div>
  </div>
</template>
<script>
import Tabs from "@/components/Tabs/Tabs.vue";
import TabPane from "@/components/Tabs/TabPane.vue";
export default {
  components: {
    Tabs,
    TabPane
  }
};
</script>
<style>
</style>
