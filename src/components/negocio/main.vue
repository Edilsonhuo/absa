<template>
    <div>
        <main>
            <div class="container">
                <div class="titulo">
                    <h1 class="h1">Impulsione o seu negocio com as nossas soluções da Banca de Negócios</h1>
                    
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
                {id:4, image:'/img/bank-building.png', descri:'Obter Capital Comercial e Circulante'},
                {id:5, image:'/img/solution.png', descri:'Soluções de Sala de Mercados '},
                {id:6, image:'/img/business-card.png', descri:'Serviços para comerciantes'},
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
        padding: 0px 4%;
        
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