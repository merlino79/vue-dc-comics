<template>
  <div class="cols">
    <div class="box-img">
      <img :src="card.thumb" :alt="card.type">
    <h3>
       {{card.type}}
    </h3>

    </div>
   

    

   
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






 
  

</style>