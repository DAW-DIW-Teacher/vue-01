<template>
    <header>
        <div class="logo">
            <img src="../assets/logo.png" width="50rem">
            <h1>PetSchool</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Precios</a></li>
                <li><a href="#">Nuestro equipo</a></li>
            </ul>
            <div>
                <button>Registro</button>
                <button class="action">Login</button>
            </div>
        </nav>
    </header>
</template>

<script>
export default {
    data() {
        return {
            email: '',
            password: '' 
        }
    }

}
</script>

<style>
header {
    display:flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    padding: 1rem;
    max-width: 1200px;
    margin: auto;
    }
header .logo {
    display:flex;
    align-items: center;
}
header h1 {
    color: #181818;
    font-size: 1.5rem;
    padding: 0rem 0.6rem;
}
header nav {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
}

header nav ul {
    display: flex;
    margin: 0rem 3rem;
}
header nav ul li {
    list-style-type: none;
    margin: 0rem 0.5rem;
}
header nav a {
    font-weight: 700;
    text-decoration: none;
    color: #181818;  
}
header nav a:hover {
    color: #ec430b;
    border-bottom: 3px solid #d1572f;
}
header nav button {
    background-color: white;
    font-weight: 700;
    color: #ec430b;
    padding: 0.6rem 1.2rem;
    cursor: pointer;
    border: 2px solid #ec430b; 
    margin: 0rem 0.3rem;
    border-radius: 0px 25px 25px;
}
header nav button.action{
    background-color: #ec430b;
    font-weight: 700;
    color: white;
    padding: 0.6rem 1.2rem;
    cursor: pointer;
    border: 2px solid #ec430b;
    margin: 0rem 0.3rem;
    border-radius: 0px 25px 25px;
}
</style>