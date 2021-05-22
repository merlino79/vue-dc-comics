<template>
  <div class="coils">

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
.coils{
  text-align: center;
}

</style>