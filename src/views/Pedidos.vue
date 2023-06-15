<template>
    <div class="content">
        <div class="pedidos">
            <h1>Gerenciar Pedidos:</h1>
            <Dashboard />
        </div>
    </div>
        <Footer />
</template>

<script>
import Dashboard from '@/components/Dashboard.vue';
import Footer from '@/components/Footer.vue';

export default {
    name: "Pedidos",
    components: {
        Dashboard,
        Footer
    }
}
</script>

<style scoped>
h1 {
    margin-top: 50px;
}

footer {
    position: absolute;
    bottom: 0;
}
</style>