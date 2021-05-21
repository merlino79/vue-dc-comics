<template>
  <div id="app">

    <Header />
    <Main />
    <Comics />
    <Footer />
    <FooterBotton />
    
    
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Comics from '@/components/Comics.vue'
import Footer from '@/components/Footer.vue'
import FooterBotton from '@/components/FooterBotton.vue'



export default {

  name: 'App',

  components: {
    Header,
    Main,
    Comics,
    Footer,
    FooterBotton,
    
    
  }
}
</script>

<style lang="scss">

@import './assets/style/general.scss';
@import './assets/style/utilitis.scss';




</style>

