<template>
    <div class="main-content">
        <div class="burger-img"></div>
        <h1>Lojas</h1>
        <div class="info">
            <h2>Brasilia</h2>
            <div class="cidade">
                <p class="nome">Aguas claras</p>
                <p class="endereco">Av. das Castanheiras - Complexo Vila Sézamo, Rua 123 B</p>
            </div>
            <div class="cidade">
                <p class="nome">Asa Sul</p>
                <p class="endereco">CLN 999 Bloco Z</p>
            </div>
            <div class="cidade">
                <p class="nome">Asa Norte</p>
                <p class="endereco">CLS 989 Bloco C</p>
            </div>
        </div>
    </div>
    <footer>
        <a href="">PEÇA ONLINE!</a>
        <a href=""><img src="https://static.wixstatic.com/media/4c4a08_7e18a5a3cdf44726923240f39f377992~mv2.png/v1/fill/w_40,h_40,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/4c4a08_7e18a5a3cdf44726923240f39f377992~mv2.png" alt=""></a>
        <a href=""><img src="https://static.wixstatic.com/media/81af6121f84c41a5b4391d7d37fce12a.png/v1/fill/w_40,h_40,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/81af6121f84c41a5b4391d7d37fce12a.png" alt=""></a>
    </footer>
</template>
<script>
export default {
    name: 'About'
}
</script>
<style scoped>

.main-content {
    background-color: #111;
}
.burger-img {
    background-image: url('/public/img/burger2.png');
    background-position: 0 -200px;
    background-size: cover;
    background-repeat: no-repeat;
    height: 800px;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    margin: 0 60px;
}

h1, h2 {
    color: #ee9b00;
}

h2 {
    text-align: center;
    font-size: 28px;
    margin-bottom: 30px;
}

p {
    color: #ee9b00;
}

.cidade {
    display: flex;
    justify-content: center;
    gap: 30px;
}

.nome {
    white-space: nowrap;
    justify-self: flex-end;
}

.info {
    max-width: 400px;
    margin: 0 auto;
}

p {
    font-size: 24px;
    color: #eee;
    margin-bottom: 30px;
}

footer {
    background-color: #222;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: flex-end;
}

footer a {
    margin-right: 30px;
    text-decoration: none;
    color: #eee;
    transition: .5s;
}

footer a:hover {
    color: #ee9b00;
}
</style>