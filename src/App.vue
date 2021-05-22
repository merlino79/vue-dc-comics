<template>
  <div id="app">

    <Header :menu="links" />
    <Main />
    <Comics />
    <Footer />
    <FooterBotton />
    <ProductCard />
    
    
  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Main from '@/components/Main.vue'
import Comics from '@/components/Comics.vue'
import Footer from '@/components/Footer.vue'
import FooterBotton from '@/components/FooterBotton.vue'
import ProductCard from '@/components/ProductCard.vue'



export default {

  name: 'App',
  data(){
    return{
      links:[{
          text: 'characters',
          url: '#',
          current: false 
        },
        {
          text: 'comics',
          url: '/',
          current: true
        },
        {
          text: 'Movies',
          url: '#',
          current: false 
        },
        {
          text: 'tv',
          url: '#',
          current: false 
        },
        {
          text: 'games',
          url: '#',
          current: false 
        },
        {
          text: ' collectibles',
          url: '#',
          current: false 
        },
        {
          text: ' videos',
          url: '#',
          current: false 
        },
        {
          text: ' fans',
          url: '#',
          current: false 
        },
        {
          text: 'news',
          url: '#',
          current: false 
        },
        {
          text: ' shop',
          url: '#',
          current: false 
        },
      ]

    }
  },

  components: {
    Header,
    Main,
    Comics,
    Footer,
    FooterBotton,
    ProductCard,
    
    
  }
}
</script>

<style lang="scss" >

@import './assets/style/general.scss';
@import './assets/style/utilitis.scss';




</style>

