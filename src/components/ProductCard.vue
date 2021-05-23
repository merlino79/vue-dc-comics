<template>

   <div class="cols">

       <img :src="card.thumb" :alt="card.type">
    
       
      
           
              
     

   

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
  flex-basis: calc(100% / 4 ) ;
}







 
  

</style>