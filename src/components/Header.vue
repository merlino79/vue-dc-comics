<template>

<header class="cols container">

    <a href="/">
    <img src="../assets/img/dc-logo.png" alt="">
  

    </a>
   
    <ul>
      <li v-for="(link, index) in menu" :key="index">
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
  
  props:{
        menu: Array
      },

  data(){

    return{
      links: [],
      
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