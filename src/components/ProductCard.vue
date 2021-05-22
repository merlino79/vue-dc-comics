<template>

   <div class="cols">
     <ul>
       <li>
         <a href="/">
             <img :src="card.thumb" :alt="card.type">
              
         </a>

       </li>
     </ul>
   

   </div>
    


   

    

   

</template>

<script>
export default {
  name: 'ProductCard',
  props:{
    card: Object
  }

}
</script>

<style labg="scss" scoped>
.cols{
  
  width: 100%;
  
  
}







 
  

</style>