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
  import Main from '../components/investimento/main.vue'
  import Card from '../components/investimento/card.vue'
  import Mais from '../components/investimento/mais.vue'
  import Footer from '../components/investimento/footer.vue'
  import Form from '../components/investimento/form.vue'
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