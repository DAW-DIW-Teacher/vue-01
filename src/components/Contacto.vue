<template>
<section id="contacto">
    <div class="formulario">
        <p>¿Necesitas más información?</p>
        <h1>Contacta con nosotros</h1>
        <form>
            <input type="text" name="nombre" placeholder="Nombre">
            <input type="text" name="email" placeholder="E-mail">
            <textarea name="mensaje" placeholder="Menssage"></textarea>
            <button>ENVIAR</button>
        </form>

    </div>
    <div class="imagen">
        <img src="../assets/gato.png" >
    </div>
</section>
</template>

<script>
export default {

}
</script>

<style>
section#contacto {
    display: flex;
    justify-content: flex-end;
    align-items: flex-start;
}
section#contacto .formulario {
    margin: 1rem;
    flex: 0 0 480px;
    background-color: #f2f2f4;
    border-radius: 25px;
    padding:1rem;

}
section#contacto .formulario p{
    padding:0px;
    font-size: 1.5rem;
    color: #ed6436;
    font-weight: 700;
}
section#contacto .formulario h1{
    font-size: 2.5rem;
    font-weight: 900;
}
section#contacto .formulario input[type=text] {
    margin-top: 1rem;
    border: none;
    outline: none;
    width: 100%;
    padding: 1rem 1.5rem;
    border-color: #f2f2f4;
    color: #181818;
    outline: none;
    line-height: 1.4rem;
    border-radius: 25px;
    font-size: 1.2rem;
    
}
section#contacto .formulario textarea {
    margin-top: 1rem;
    border: none;
    resize: none;
    width: 100%;
    height: 200px;
    padding: 1rem 1.5rem;
    border-color: #f2f2f4;
    color: #181818;
    outline: none;
    line-height: 1.4rem;
    border-radius: 25px;
    font-size: 1.2rem;
    
}
section#contacto .formulario button {
    background-color: #ec430b;
    font-weight: 700;
    color: white;
    padding: 0.6rem 1.2rem;
    cursor: pointer;
    border: 2px solid #ec430b;
    margin: 1rem 0.3rem;
    border-radius: 0px 25px 25px;

}
section#contacto img {
    width: 100%;
    max-width: 1000px;
}

section#contacto .imagen {
    align-self: center;
    flex: 0 1 auto;

}
 

</style>