<template>

<header class="cols container">

    <a href="/">
    <img src="../assets/img/dc-logo.png" alt="">
    </a>
    <ul>
      <li v-for="(link, index) in links" :key="index">
       <a :href="link.url"
       :class="{'active': link.current}"
       >
         {{link.text}}
       </a>
      </li>
      
      
    </ul>

  
    
 </header>
  

 

  
</template>

<script>
export default {
  name: 'Header',
  data(){
    return{
      links: [
        {
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
  }

}
</script>

<style  lang="scss" scoped>
.cols{

  display: flex;
  height: 120px;
  width: 100%;
  ul{
    width: 100%;
   
    justify-content: end;
    
    
  } 
  a{
    line-height: 120px;
    margin: 10px;
    text-transform: uppercase;
    color: #1E0000;
    &:hover,
    &.active{
      color: #0067F8;
      
     
     
    }
    
    
    
  } 
}
 
    
    
  
 
 
  
  
  
  
  
  
  
  








</style>