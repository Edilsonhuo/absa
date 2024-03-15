<template>
<div>
  <Header/>

  <router-view/>
</div>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/header.vue'

export default {
  components:{
    Header,
  }
}
</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

  *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: Helvetica;
    text-decoration: none;
  }

  h3{
    color: #2D2323;
    font-size: 40px;
    text-align: center;
  }
  h4{
    color: #2D2323;
    font-size: 20px;
    padding: 10px 0px;
  }

  

  .h1{
    font-size: 60px;
    color: #fff;
  }
  .h3{
    font-size: 44px;
    color: #fff;
    
  }

  .icon{
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .icon .mdicon{
    color: rgb(61, 60, 60);
    font-size: 8px;
  }

  .u{
    display: flex;
    align-items: center;
    gap: 49px;
    list-style: none;
  }
  .menubar ul  li{
    color: #AF144B;
  }
  .menubar ul  li a{
    text-decoration: none;
    color: rgb(56, 56, 56);
    font-size: 18px;
  }
  .menubar ul  li a:hover{
    color: #AF144B;
  }
  
</style>
