<template>
    <div>
        <main>
            <div class="container">
                <div class="titulo">
                    <h1 class="h1">Bem-vindo à Banca Corporativa e de Investimentos </h1>
                    
                </div>

                <div class="opcoes" >
                    <div class="card" v-for="dado in dados" :key="dado.id">
                        <img :src="dado.image" alt="">
                        <a href="" class="a">{{ dado.descri }}</a>
                    </div>
                </div>
            </div>
        </main>
    </div>
</template>

<script>
export default {
    name: 'Main',
    data() {
        return {
            dados: [
                {id:1, image:'/img/safe.png', descri:'Conta corrente empresarial'},
                {id:2, image:'/img/saving-account.png', descri:'Contas de poupanca'},
                {id:3, image:'/img/wallet.png', descri:'Pedir emprestimo'},
                {id:4, image:'/img/plant.png', descri:'Banca de Investimento'},
                {id:5, image:'/img/bank-building.png', descri:'Capital Circulante '},
                {id:6, image:'/img/solution.png', descri:'Soluções de Sala de Mercados '},
                {id:7, image:'/img/laptop.png', descri:'Plataforma de Gestao de Comercio Online do Absa'},
            ]            
        }
    },
}
</script>

<style scoped>
    main{
        background-image: url('/img/Maputo-night-city.jpg');
        height: auto;
        object-fit: cover;
        background-position: center;
        background-size: cover;
        opacity: 1.8;
        padding-bottom: 70px;
        padding-bottom: 110px;
    }
    .a{
        color: #fff;
        font-size: 17px;
        text-align: center;
        font-weight: 700;
    }

    .container{
        margin-top: 210px;
        display: inline-block;
        width: 100%;
        
    }
    .titulo{
        text-align: center;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        gap: 20px;
    }

    .container .opcoes{
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 20px;
        margin-top: 84px;
    }

    .opcoes .card{
        display: flex;
        flex-wrap: wrap;
        flex-direction: column;
        align-items: center;
        width: 10%;
    }

    .card .security{
        color: #fff;
        
    }
</style>