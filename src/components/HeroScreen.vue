<template>
  <section id="main">
      <div><h1>Escuela de entrenamiento de mascotas</h1><br>
      <h3>El mejor lugar para entregar y hacer disfrutar a tu mascota</h3>
      <button class="action">RESERVA AHORA</button></div>

      <div class="imagen"> 
          <img src="../assets/hero.png">
      </div>
       
  </section>
</template>

<script>
export default {

}
</script>

<style>
section#main {
    display: flex;
    flex-wrap: nowrap;
    padding: 1rem 0rem;
    justify-content: flex-end;
}

section#main .imagen {
    transform: scaleX(-1);
    flex: 0 1 50%;
}
section#main img {
    width: 100%;
}
section#main div {
    margin-left: 1rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    flex: 0 0 550px;
}
section#main h1 {
    font-size: 3rem;
    padding: 2rem 0rem;
}

section#main button.action{
    background-color: #ec430b;
    font-weight: 700;
    color: white;
    padding: 0.6rem 1.2rem;
    cursor: pointer;
    border: 2px solid #ec430b;
    margin: 2rem 0.3rem;
    border-radius: 0px 25px 25px;
}
</style>