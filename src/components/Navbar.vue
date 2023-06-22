<template>
    <div class="nav">
        <router-link to="/">
            <img :src="logo" :alt="alt" class="logo">
        </router-link>
        <div>
            <router-link to="/">Home</router-link>
            <router-link to="/pedidos">Pedidos</router-link>
            <router-link to="/about">Sobre</router-link>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
    props: ['logo', 'alt']
}
</script>

<style scoped>
.nav {
    background-color: #222;
    border-bottom: 4px solid #111;
    padding: 15px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    width: 50px;
    height: 50px;
}

.nav a {
    color: #ee9b00;
    text-decoration: none;
    margin: 12px 30px;
    transition: .5s;
    font-size: 24px;
}

.nav a:hover {
    color: #fff;
}
</style>