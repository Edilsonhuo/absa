<template>
    <div>
        <div class="formu">
            
            <div class="help">
                <div class="imag">
                    <img src="/img/house.png" alt="">
                </div>
                <div class="contact">
                    <h4 class="co">Escolha o Absa como parceiro para o seu sucesso</h4>
                    <p>Disponha de uma banca holística, soluções de cadeia de valor e suporte aos seus negócios. </p>

                    <button>Saiba mais</button>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
export default {
    name: 'Form'
}
</script>

<style scoped>
    .formu{
        text-align: center;
        width: 100%;
        padding: 99px 9%;
        background: #2d2323;
        margin-bottom: 20px;
    }
    .help{
        display: flex;
    }

    .imag{        
        width: 40%;
    }
    .imag img{
        width: 270px;
        height:200px;
    }
    .contact{
        width: 60%;
        text-align: start;
    }
    .contact .co{
        text-align: start;
        font-size: 42px;
        color: #fff;
    }
    .contact p{
        text-align: start;
        margin-top: 9px;
        color: #fff;
        font-size: 17px;
    }

    button{
        padding: 10px 18px;
        margin-top: 20px;
        border: 2px solid #fff;
        border-radius: 7px;
        background: #2d2323;
        color: #fff;
        cursor: pointer;
    }
    button:hover{
        box-shadow:0 0px 7px 0 #fff, 0 0px 7px 0 #fff;
    }
    
</style>