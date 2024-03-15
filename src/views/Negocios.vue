<template>
    <div>
      <!-- <teste/> -->
      <Main/>
      <Card/>
      <Form/>
      <Mais/>
      <Footer/>
    </div>
  </template>
  
  <script>
  // import teste from '../components/teste.vue'
  import Main from '../components/negocio/main.vue'
  import Card from '../components/negocio/card.vue'
  import Mais from '../components/negocio/mais.vue'
  import Footer from '../components/negocio/footer.vue'
  import Form from '../components/negocio/form.vue'
  export default {
    name: 'home',
    components:{
      Main,
      Card,
      Mais,
      Footer,
      Form
    }
  }
  </script>