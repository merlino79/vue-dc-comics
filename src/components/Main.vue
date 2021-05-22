<template>
<div class="cols">
  <div class="container">
   
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
  components:{
    ProductCard
    
  },
  data(){
    return{
      products
    }
  },
  mounted(){
    console.log(products);
  }


}
</script>

<style lang="scss" scoped>

.cols{
  width: 100%;
  height: 140px;
  line-height: 140px;
   background-color: #1C1C1C;
  h3{
    color: azure;
  }
}


</style>