<template>
  <section id="precios">
      <h1 class="titulo">Nuestros precios</h1>
      <div class="lista">
          <div class="columna">
              <div class="titulo">
                  <p>Servicios Básicos</p>
              </div>
              <div class="producto">
                  <div class="articulo">
                    <p>ENTRENAMIENTO PERROS</p>
                    <div class="linea"></div>
                    <div class="precio">20 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
                <div class="producto">
                  <div class="articulo">
                    <p>ENTRENAMIENTO GATOS</p>
                    <div class="linea"></div>
                    <div class="precio">18 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
                <div class="producto">
                  <div class="articulo">
                    <p>ALOJAMIENTO PERROS</p>
                    <div class="linea"></div>
                    <div class="precio">36 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
                <div class="producto">
                  <div class="articulo">
                    <p>ALOJAMIENTO GATOS</p>
                    <div class="linea"></div>
                    <div class="precio">32 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
          </div>
          <div class="columna">
                            <div class="titulo">
                  <p>Servicios Premium</p>
              </div>
              <div class="producto">
                  <div class="articulo">
                    <p>ALOJAMIENTO CON CUIDADOS MÉDICOS</p>
                    <div class="linea"></div>
                    <div class="precio">45 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
                <div class="producto">
                  <div class="articulo">
                    <p>RECOGIDA Y ENTREGA</p>
                    <div class="linea"></div>
                    <div class="precio">24 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
                <div class="producto">
                  <div class="articulo">
                    <p>SUPERVISIÓN POR WEBCAM</p>
                    <div class="linea"></div>
                    <div class="precio">10 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
                <div class="producto">
                  <div class="articulo">
                    <p>ALOJAMIENTO DE ANIMÁLES EXÓTICOS</p>
                    <div class="linea"></div>
                    <div class="precio">30 €</div>
                  </div>
                  <div class="texto">Testo de relleno para este elemento muy chulo</div>
                </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
section#precios {
  max-width: 1200px;
  margin: auto;
}
section#precios .lista {
    display: flex;
}
section#precios .lista .columna {
    flex: 1 1 50%;
}
section#precios .lista .columna .texto {
    padding-right: 1rem;
    font-weight: 300;
}
section#precios .lista .titulo{
    font-size: 1.5rem;
    font-weight: 700;
}
section#precios .lista .producto {
    padding: 1rem;
    font-weight: 700;
}
section#precios .lista .producto .articulo{
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
}
section#precios .lista .producto p {
    padding: 0rem;
    font-size: 1.2rem;
    color: #ec430b;
}
section#precios .lista .producto .linea {
    margin-bottom: 8px;
    display:flex;
    flex: 1 1 auto;
    background-image: radial-gradient(circle closest-side, #4e4e4e 99%, rgba(255, 255, 255, 0) 1%);
    background-size: 12px 2px;
    background-repeat: repeat;
    height: 2px;

}
section#precios .lista .producto .precio {
    font-size: 1.2rem;
    font-weight: 700;
}
</style>