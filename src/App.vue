<template>
    <div class="content">
        <Navbar :logo="logo_src" :alt="app_name" />
        <RouterView />
    </div>
</template>

<script>
import Navbar from './components/Navbar.vue';

export default {
    name: 'App',
    components: {
        Navbar,
    },
    data() {
        return {
            logo_src: '/img/logo.png',
            app_name: 'Make Your Burger '
        }
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

* {
    font-family: 'Roboto';
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


.main-container {
    margin: 50px;
    min-height: 250px;
}

h1 {
    text-align: center;
    font-size: 42px;
    margin-bottom: 30px;
    color: #222;
}
</style>