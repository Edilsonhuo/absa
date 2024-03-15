<template>
    <div>
        <nav class="navegacao">

            <div class="menu">
                <div class="logo">
                    <img src="/img/ABSA.png" alt="">

                    <div class="menubar">
                        <ul class="u">
                            <li>
                            <router-link to="/">Banca Pessoal</router-link>
                            </li>
                            <li>
                                <router-link to="/negocio">Banca de Negócios</router-link>
                            </li>
                            <li>
                                <router-link to="/investimento">Corporativa e de Investimento</router-link>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="menubar">
                        <ul class="u">
                            <li>PT</li>
                            <div class="icon">
                                <mdicon name="magnify" class="mdicon"/>
                                <li><a href="">Search</a></li>
                            </div>
                            <div class="icon">
                                <mdicon name="arrowCollapseRight" class="mdicon" />
                                <li><a href="">Entrar</a></li>
                            </div>
                            
                        </ul>
                </div>
            </div>

            <div class="menu2">
                
                <div class="nav1">
                    <ul class="u">
                        <li><a href="">Contas</a></li>
                        <li><a href="">Cartões de crédito</a></li>
                        <li><a href="">Solicitar empréstimo</a></li>
                        <li><a href="">Seguro</a></li>
                    </ul>
                </div>

                <div class="btn"><button>Contacte-nos</button></div>
            </div>

        </nav>
    </div>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style scoped>
    .navegacao{
        top: 0;
        position: fixed;
        width: 100%;
    }

    .menu{
        display: flex;
        align-items: center;
        background: white;
        padding: 10px 3%;
        justify-content: space-between;
    }
    .menu .logo{
        display: flex;
        gap: 47px;
    }
    .menu .logo img{
        width: 45px;
        height: 45px;
    }
    .menu .logo .menubar{
        border-left: 1px solid rgb(185, 183, 183);
        padding-left: 7px;
    }

    .menu .menubar{
        display: flex;
    }

    .navegacao .menu2{
        background: #AF144B;
        display: flex;
        justify-content: space-between;
        padding: 17px 3%;
        align-items: center;
    }

    .menu2 ul li a{
        color: #fff;
        font-size: 18px;
        text-decoration: none;
    }
    .menu2 ul li a::after{
        content: " ";
        background-color: #fff;
        height: 4px;
        width: 0%;
        display: block;
        margin: 0 auto;
        transition: 0.4s;
    }
    .menu2 ul li a:hover::after{
        width: 100%;
    }

    .menu2 .btn{
        padding: auto;
        display: inline-block;
        align-content: end;
        position: absolute;
        right: 0%;

    }
    .btn button{
        padding: 18px 18px;
        font-size: 15px;
        background: #870A3C;
        border: none;
        cursor: pointer;
        color: #fff;
        font-weight: 900;
    }

    .btn button{
        animation: animate-outline 1s ease-out infinite;
    }
    
    .btn button:hover{
        background-color: #870A3C;
    }
    
    @keyframes animate-outline {
        from{
            outline: 0px solid #af144abd;
        }to{
            outline: 7px solid #af144a93 ;
        }
    }



    
</style>