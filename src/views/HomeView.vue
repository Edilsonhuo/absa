<template>
  <div>
    <!-- <teste/> -->
    <Main/>
    <Card/>
    <Mais/>
    <Footer/>
  </div>
</template>

<script>
// import teste from '../components/teste.vue'
import Main from '../components/bPessoal/main.vue'
import Card from '../components/bPessoal/card.vue'
import Mais from '../components/bPessoal/mais.vue'
import Footer from '../components/bPessoal/footer.vue'
export default {
  name: 'home',
  components:{
    Main,
    Card,
    Mais,
    Footer
  }
}
</script>
