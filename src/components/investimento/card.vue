<template>
    <div>
        <h3>Mais soluções com as quais podemos ajudá-lo</h3>
        <div class="dados">

           <div class="card" v-for="dado in dados" :key="dado.id">
            <div class="cards">
                <mdicon :name="dado.image" class="mdicon"/>
                <p>{{ dado.descricao }}</p>
                <a href="">{{ dado.btn }}</a>
            </div>
           </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Card',
    data() {
        return {
            dados:[
                {id:1, image:'laptop', descricao:'Internet banking', btn:'Entar'},
                {id:2, image:'phone', descricao:'Contacte-nos', btn:'Quero saber mais'},
                {id:2, image:'cellphone', descricao:'Banca Digital', btn:'Quero saber mais'},
                {id:4, image:'currencyUsd', descricao:'Rates and currencies', btn:'Quero saber mais'},
                {id:5, image:'fileDocumentCheckOutline', descricao:'Tarifas, Taxas e Câmbios', btn:'Quero saber mais'},
                {id:6, image:'security', descricao:'Segurança Online', btn:'Quer saber mais'}
            ] 
        }
    },
}
</script>

<style scoped>
    div{
        padding: 40px 0px;
    }
    .dados{
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .card{
        display: flex;
        justify-content: center;
        flex-flow: row wrap;
        flex-direction: row;
        margin: 9px;
    }
    .card .cards{
        display: flex;
        flex-direction: column;
        justify-content: center;
        justify-items: center;
        align-items: center;
        gap: 28px;
        padding: 0px 7px;
        padding-top: 9px;
        border-radius: 7px;
        transition: .7s;
        box-shadow:0 4px 8px 0 #af144aa4, 0 16px 17px 0 #af144a63; 
    }
    .cards p, a{
        font-size: 18px;
        font-weight: bold;
        color: #2D2323;
    }
    .cards a{
        padding: 6px 6px;
        border-top-left-radius: 7px;
        border-top-right-radius: 7px;
        background: #af144ada;
        color: #fff;
    }

</style>