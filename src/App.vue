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

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
 
}

.container{
  max-width: 1170px;
  margin: 0 auto;
  
}
ul{
  list-style: none;
   display: flex;
}
a{
   text-decoration: none;
}

img{
  max-width: 100%;
}

</style>

