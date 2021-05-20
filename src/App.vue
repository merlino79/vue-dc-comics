<template>
  <div id="app">

    <Header />
    <Main />
    
    
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'



export default {

  name: 'App',

  components: {
    Header,
    Main,
    
    
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

</style>

