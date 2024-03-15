<template>
    <div>
        <footer>
            <p>&copy; Copyright. Absa Bank Moçambique, SA (registado sob o número 101220982) é regulado pelo Banco de Moçambique. Todos os direitos reservados.</p>
            <div class="app">
                <h3 class="exp">Experience banking at your fingertips</h3>
                <div class="download">
                    <img src="/img/appstore.png" alt="">
                    <img src="/img/Google.png" alt="">
                </div>

                <div class="footer">

                </div>
            </div>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'Footer'
    
}
</script>

<style  scoped>
    div{
        width: 100%;
        padding-top: 70px;
    }
    footer{
        width: 100%;
        text-align: center;
    }
    p{
        color: #979797;
        font-size: 16px;
    }

    .app{
        margin-top: 20px;
        text-align: center;
        padding-bottom: 50px;
    }
    .exp{
        color: #2D2323;
        font-size: 25px;
      }
      .download{
        margin-top: 24px;
        padding: 0px;
      }
      .download img{
        width: 109px;
        height: 40px;
        cursor: pointer;
        margin: 7px;
      }

      .footer{
        padding: 0;
        width: 100%;
        height: 22px;
        margin-top: 40px;
        background: linear-gradient(45deg, #960528,#AA052D,#BE0028,#DC0032,#F52D28,#FA551E,#FF780F,#F0325A,#AF144B,#870A3C,#640032);
        
      }

      /*
      
      #960528
      #AA052D
      #BE0028
      #DC0032
      #F52D28
      #FA551E
      #FF780F
      #F0325A
      #AF144B
      #870A3C
      #640032
      
      */
    
</style>