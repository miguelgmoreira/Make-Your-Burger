<template>
    <div class="main-banner">
        <h1>Make Your Burger</h1>
    </div>
</template>

<script>
    export default {
        name: 'Banner'
    }
</script>

<style scoped>

.main-banner {
    background-image: url('/public/img/burger.jpg');
    background-position: 0 -400px;
    background-size: cover;
    background-repeat: no-repeat;
    height: 650px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
}

.main-banner h1 {
    color: #fff;
    text-align: center;
    font-size: 60px;
    background-color: #222;
    padding: 25px 40px;
}

</style>