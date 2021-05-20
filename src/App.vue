<template>
  <div id="app">

    <Header />
    <Main />
    <Comics />
    <Footer />
    
    
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Comics from '@/components/Comics.vue'
import Footer from '@/components/Footer.vue'



export default {

  name: 'App',

  components: {
    Header,
    Main,
    Comics,
    Footer,
    
    
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
  max-width: 80%;
  margin: 0 auto;
  
}
ul{
  list-style: none;;
}
a{
   text-decoration: none;
}

img{
  max-width: 100%;
}

</style>

