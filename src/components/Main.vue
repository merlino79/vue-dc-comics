<template>
<div class="cols">
  <div class="ac-container">
    
                  <ProductCard 
     v-for="(product, index) in products"
     :key="index"
     :card="product"
     />

   
  </div>  

</div>   
   
</template>

<script>

import products from "@/assets/data/dc-comics.js"; 
import ProductCard from "@/components/ProductCard"; 

export default {

  name: 'Main',
   components: { ProductCard },

  
  data(){
    return{
      products
    }
  },
  mounted(){
    //console.log(products);
  }


}
</script>

<style lang="scss" scoped>

.cols{
  
 
  
 
  height: 100%;
  background-color: black;
  
  
}  
.ac-container{
  
  display: flex;
  flex-wrap: wrap;
  
  justify-content: space-around;
  
}
  
 
  //  background-image: url(../assets/img/jumbotron.jpg);
   

 
 
  



</style>
   
   
  
   

    

    
    

     
     


  
     


  
  
  
 
  



  
