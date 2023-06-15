<template>
    <Banner />
    <div class="main-container">
        <h1>Monte o seu burger:</h1>
        <BurgerForm />
    </div>
    <Footer />
</template>

<script>
import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';
import Footer from '@/components/Footer.vue';
export default {
    name: 'Home',
    components: {
    Banner,
    BurgerForm,
    Footer
}
}
</script>