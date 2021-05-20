<template>
<footer>
  <!-- <img src="../assets/img/footer-bg.jpg" alt="footer-bg"> -->
   
  <div class="cols">
  
    <div class="footer-up container">
       
   
      <div class="link">
        <div class="dc-comics">
        <h3>
          dc comics
        </h3>
       <ul>
         <li>
           <a href="#">
             Characters
           </a>
         </li>
         <li>
           <a href="#">
             Comics
           </a>
         </li>
         <li>
           <a href="#">
             Movies
           </a>
         </li>
         <li>
           <a href="#">
             TV
           </a>
         </li>
         <li>
           <a href="#">
             Games
           </a>
         </li>
         <li>
           <a href="#">
             Videos
           </a>
         </li>
         <li>
           <a href="#">
            News
           </a>
         </li>
       </ul>
      </div>
      <div class="dc">
        <h3>
          dc
        </h3>
      </div>
      <div class="sites">
        <h3>
          sites
        </h3>
      </div>

      </div>
       
      
     
       
       
          
      
     
    </div>
  </div>
  

  
  
</footer>

  
</template>

<script>
export default {
  name: 'Footer'

}
</script>

<style lang="scss" scoped>
.cols{
  background-image: url(../assets/img/footer-bg.jpg);
  width: 100%;
  height: 350px;
  background-color: #3f443f;
  .link{
    display: flex;
    justify-content: space-between;
   
    width: 30%;
    
  }
  ul{
    display: block;
  }
  a{
    color: #879587;
  }
  .dc-comics,
  .dc,
  .sites{
    color: white;
    margin-top: 50px;
  }

  
    
    
    
 


  

   
  
  
   
   
 


}

  
  
  
  




</style>