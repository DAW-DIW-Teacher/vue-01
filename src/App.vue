<template>
  <MenuPrincipal/>
  <HeroScreen/>
  <Servicios />
  <Precios />
</template>

<script>
import MenuPrincipal from './components/MenuPrincipal.vue'
import HeroScreen from './components/HeroScreen.vue'
import Servicios from './components/servicios/Servicios.vue'
import Precios from './components/Precios.vue'

export default {
  name: 'App',
  components: {MenuPrincipal, HeroScreen, Servicios, Precios}
  }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;700;800&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: 'Nunito', sans-serif;
}

</style>
