<template>
<div class="cols">
  <div class="container">
    <div class="comics">
      <ul>
      <li>
        <img src="../assets/img/buy-comics-digital-comics.png" alt="comics">
        <a href="#">digital comics</a>
      </li>
       <li>
         <img src="../assets/img/buy-comics-merchandise.png" alt="comics">
        <a href="#">dc merchandise</a>
      </li>
       <li>
        <img src="../assets/img/buy-comics-subscriptions.png" alt="comics">
        <a href="#">subscription</a>
      </li>
       <li>
        <img src="../assets/img/buy-comics-shop-locator.png" alt="comics">
        <a href="#">comic shop locator</a>
      </li>
       <li>
        <img src="../assets/img/buy-dc-power-visa.svg" alt="comics">
        <a href="#">dc power visa</a>
      </li>

    </ul>

    </div>
    
   

  </div>
 

</div>
  
</template>

<script>
export default {
  name: 'Comics'

}
</script>

<style lang="scss" scoped>

.cols{
  position: relative;
  height: 160px;
  line-height: 160px;
  width: 100%;
  background-color: #0282F9;
 
}
.comics{
   
   width: 85%;
   flex-basis: calc(100% / 5);
 

}
ul{
  
  justify-content: space-between;
 
  
  a{
    top: 0%;
    text-transform: uppercase;
  position: absolute;
  margin-left: 10px;
  color: white;
}
}
img{
  
  width: 50px;
  height: 70px;
  margin-top: 30px;
  
}


</style>
