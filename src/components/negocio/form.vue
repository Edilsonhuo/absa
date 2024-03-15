<template>
    <div>
        <div class="formu">
            <h3>Está interessado numa solução da nossa Banca de Negócios?</h3>
            <h4>Preencha o formulário abaixo para começar</h4>
            <div class="formul">
                <form action="">
                    <div class="form1">
                        <label for="">Qual é o nome da sua empresa? *</label>
                        <input type="text" placeholder="Digite o nome da empresa">
                    </div>

                    <div class="form1">
                        <label for="">Há quanto tempo a sua empresa opera? *</label>
                        <input type="text" placeholder="Insira anos activos">
                    </div>

                    <div class="form1">
                        <label for="">Quanto sua empresa factura anualmente? *</label>
                        <select name="" id="">
                            <option value="1" selected>Menos que 50,000,000,00 MT</option>
                            <option value="1" >80,000,000,00 MT - 249,000,000,00 MT</option>
                            <option value="1" >250,000,000,00 MT - 750,000,000,00 MT</option>
                        </select>
                    </div>

                    <div class="form1">
                        <label for="">Onde é que a sua empresa está localizada? *</label>
                        <input type="text" placeholder="Digite a cidade ou area">
                    </div>

                    <div class="form1">
                        <label for="">Qual é o endereço de e-mail que podemos utilizar para entrar em contato com a sua empresa? *</label>
                        <input type="text" placeholder="Digite um endereco de e-mail valido">
                    </div>

                    <div class="form1">
                        <label for="">Qual é o número de telefone que podemos utilizar para entrar em contato com a sua empresa? *</label>
                        <input type=" tel">
                    </div>
                    <div class="form1">
                        <button type="submit">Submeter</button>
                    </div>
                </form>
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
        padding: 20px 0px;
        text-align: center;
        width: 100%;
    }
    .formul{
        padding: 20px 4%;
        width: 100%;
        display: flex;
        justify-content: center;
    }
    form .form1{
        display: flex;
        flex-direction: column;
        align-items: start;
        gap: 4px;
        margin: 40px 0px;
        width: 100%;
    }
    .form1 input, select{
        width: 100%;
        height: 48px;
        font-size: 15px;
        padding: 0px 10px;
        border: 1px solid rgba(128, 128, 128, 0.664);
        border-radius: 7px;
        outline: none;
    }
    select{
        cursor: pointer;
    }
    option{
        color: rgba(128, 128, 128, 0.664);
    }
    .form1 label{
        font-size: 18px;
        color: #2D2323;
    }

    button{
        padding: 11px 17px;
        border: none;
        outline: none;
        cursor: pointer;
        color: #fff;
        background: #af144aa9;
        border-radius: 7px;
    }
</style>