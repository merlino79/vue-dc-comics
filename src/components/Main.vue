<template>
<div class="cols">
  <div class="container">
    <ul>
      <li>
                  <ProductCard 
     v-for="(product, index) in products"
     :key="index"
     :card="product"
     />

      </li>
    </ul>

    
   

   
   
  
   

    

    
    

     
     


  </div>
  
     


  
  
  
 
  
</div>


  
</template>

<script>

import products from "@/assets/data/dc-comics.js"; 
import ProductCard from "@/components/ProductCard"; 

export default {

  name: 'Main',
  components:{
    ProductCard
    
  },
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
  
  width: 100%;
  height: 300px;
  background-color: black;
  
  
 
  //  background-image: url(../assets/img/jumbotron.jpg);
   

 
  h3{
    color: azure;
  }
  
}


</style>