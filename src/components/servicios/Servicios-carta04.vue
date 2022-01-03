<template>
  <div class="carta">
    <div class="imagen">
        <span class="material-icons">home</span>
    </div>
    <h1>Taxi para animales</h1>
    <p> Esto es un ejemplo de texto que podemos poner aquí para ver como va</p>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
div.carta {
    background-color: #aff0f6;
    border-radius: 25px;
    margin:1rem;
    flex: 0 0 16rem;
}
div.carta .imagen{
    min-height: 80px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA4MDAgMjMwJz4gPHBhdGggZmlsbD0nI2ZmZmZmZicgZmlsbC1vcGFjaXR5PScwLjQnIGQ9J00wLDIyNEw2MCwyMjRDMTIwLDIyNCwyNDAsMjI0LDM2MCwxOTJDNDgwLDE2MCw2MDAsOTYsNzIwLDU4LjdDODQwLDIxLDk2MCwxMSwxMDgwLDMyQzEyMDAsNTMsMTMyMCwxMDcsMTM4MCwxMzMuM0wxNDQwLDE2MEwxNDQwLDBMMTM4MCwwQzEzMjAsMCwxMjAwLDAsMTA4MCwwQzk2MCwwLDg0MCwwLDcyMCwwQzYwMCwwLDQ4MCwwLDM2MCwwQzI0MCwwLDEyMCwwLDYwLDBMMCwwWic+PC9wYXRoPjwvc3ZnPg==);
    border-radius: 25px 25px 0px 0px;
    text-align: center;
}
div.carta .imagen span {
    font-size: 4rem;
    padding-top: 0.5rem;
}

div.carta h1,p {
    padding: 1rem;
}

</style>