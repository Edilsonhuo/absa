<template>
    <div >
        <div class="ferramenta">
            <div class="dado">
                <h4>Ferramentas Uteis</h4>
            <ul>
                <li><a href="">Fale connosco</a></li>
                <li><a href="">Tarifas, Taxas e Câmbios</a></li>
                <li><a href="">Apoio no banco digital</a></li>
                <li><a href="">Relatório do Sector Global</a></li>
                <li><a href="">do Petróleo e do Gás</a></li>
                <li><a href="">Calculadora de empréstimo pessoal</a></li>
                <li><a href="">Calculadora de empréstimo à habitação</a></li>
                <li><a href="">Políticas de Negóci</a></li>
            </ul>
            </div>
            <div class="dado">
                <h4>As nossas soluções bancárias</h4>
            <ul>
                <li><a href="">Banca Pessoal</a></li>
                <li><a href="">Banca Premier</a></li>
                <li><a href="">Banca de Negócios</a></li>
                <li><a href="">anca Corporativa e de Investimento</a></li>
                <li><a href="">Banca no local de trabalho Gás</a></li>
                <li><a href="">App, online e outros serviços bancários</a></li>
            </ul>
            </div>
            <div class="dado">
                <h4>Conheça-nos</h4>
            <ul>
                <li><a href="">Sobre o Absa Bank Moçambique</a></li>
                <li><a href="">Sobre Absa Group</a></li>
                <li><a href="">Carreiras</a></li>
                <li><a href="">Demonstrações Financeiras</a></li>
                <li><a href="">Literacia Financeira</a></li>
            </ul>
            </div>
            <div class="dado">
                <h4>Suporte</h4>
            <ul>
                <li><a href="">Contacte-nos</a></li>
                <li><a href="">Dê-nos a sua opinião</a></li>
                <li><a href="">Requisitos do Navegador</a></li>
                <li><a href="">Segurança Online</a></li>
                <li><a href="">Tratamento de reclamações</a></li>
            </ul>
                <h4 style="margin-top: 30px;">Jurídico</h4>
            <ul>
                <li><a href="">Declaração de privacidade</a></li>
                <li><a href="">Política de cookies</a></li>
                <li><a href="">Termos de uso do site</a></li>
            </ul>
            </div>
            <div class="dad">
                <div class="redes">
                    <a href=""><img src="/img/facebook-50.png" alt="" /></a>
                    <a href=""><img src="/img/twitter-50.png" alt="" /></a>
                    <a href=""><img src="/img/youtube.png" alt=""></a>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name:'Mais'
}
</script>

<style scoped>

    .ferramenta{
        display: flex;
        padding: 10px 3%;
        justify-content: center;
        gap: 70px;
        width: 100%;
        box-shadow:0 4px 7px 0 #af144ac0, 0 0px 7px 0 #af144a96;
        

    }
    /*.ferramenta .dado{
        border: 1px solid black;
    }*/
    .ferramenta .dad{
        width: 40px;
    }
    .ferramenta .dado h4{
        font-size: 17px;
        margin-bottom: 18px;
        color: #2D2323;
    }
    .ferramenta .dado ul li{
        list-style: none;
        padding-bottom: 10px;
    }
    .ferramenta .dado ul li a{
        color: #2D2323;
        font-size: 15px;

    }
    .dad .redes{
        display: flex;
        flex-direction: column;
        align-items: end;
        justify-content: end;
        gap: 14px;
    }
    .redes img{
        width: 30px;
        height: 30px;
    }

</style>