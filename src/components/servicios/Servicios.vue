<template>
<section id="servicios">
  <h1 class="titulo">Nuestros servicios</h1>
  <div class="cartas">
    <Hotel/>
    <Comida/>
    <Actividades/>
    <Taxi/>
  </div>
</section>
</template>

<script>
import Hotel from './Servicios-carta01.vue'
import Comida from './Servicios-carta02.vue'
import Actividades from './Servicios-carta03.vue'
import Taxi from './Servicios-carta04.vue'
export default {
  components: { Hotel, Comida, Actividades, Taxi}
}
</script>

<style>
section#servicios {
  max-width: 1200px;
  margin: auto;
  }
section h1.titulo {
  text-align: center;
  font-size: 3.2rem;
  margin: 2rem 0rem;
  font-weight: 800;
}


section#servicios div.cartas {
  display:flex;
  flex-wrap: wrap;
  justify-content: center;
  height: 20rem;
}
</style>