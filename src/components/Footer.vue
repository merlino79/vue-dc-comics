<template>
<footer>
  
   
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
       <div class="shop">
         <h3>
           Shop
         </h3>
         <ul>
           <li>
             <a href="#">
               Shop Dc
             </a>
           </li>
           <li>
             <a href="#">
               Shop Dc Collection
             </a>
           </li>
         </ul>

        </div>
        </div>
        
        <div class="dc">
        <h3>
          dc
        </h3>
        <ul>
         <li>
           <a href="#">
             Terms Of Use
           </a>
         </li>
         <li>
           <a href="#">
             Terms Of polici (new)
           </a>
         </li>
         <li>
           <a href="#">
             Add Choes
           </a>
         </li>
         <li>
           <a href="#">
             Advertisting
           </a>
         </li>
         <li>
           <a href="#">
             Subscription
           </a>
         </li>
         <li>
           <a href="#">
             Talent Workshopes
           </a>
         </li>
         <li>
           <a href="#">
            CPSC Certificates
           </a>
         </li>
          <li>
           <a href="#">
            Ratings
           </a>
         </li>
          <li>
           <a href="#">
            Shop Helps
           </a>
         </li>
          <li>
           <a href="#">
            Contact US
           </a>
         </li>
       </ul>
         </div>
        <div class="sites">
        <h3>
          Sites
        </h3>
        <ul>
          <li>
            <a href="#">
              DC
            </a>
            <li>
            <a href="#">
              MAD Magazine
            </a>
          </li>
           <li>
            <a href="#">
              DC Kings
            </a>
          </li>
           <li>
            <a href="#">
             DC Universe
            </a>
          </li>
           <li>
            <a href="#">
              DC Power Visa
            </a>
          </li>
          
          
        </ul>
        
         </div>

      </div>

      <div class="img-logo">

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
  height: 370px;
  background-color: #3f443f;
  .link{
    display: flex;
    justify-content: space-between;
    
    width: 40%;
    
  }
  ul{
    display: block;
    
      
    
    
   
  }
  li{
     margin-bottom: 5px;
    a{
     
      color: #879587;
    }
  }

  .footer-up{
    width: 100%;
    height: 100%;
    display: flex;
  }
 

   

 
  .dc-comics,
  .dc,
  .sites{
    color: white;
   
    margin-top: 35px;
    >h3{
      margin-bottom: 20px;
    }
    .shop{
      margin-top: 20px;
      >h3{
        margin-bottom: 20px;

      }
    }
     
  }

  .img-logo{
   
   
     background-image: url(../assets/img/dc-logo-bg.png);
     background-size: 80%;
     background-repeat: no-repeat;
     background-position: center;

     
     
     width: 50%;
     height: 100%;
     
    
    
     

  }
  
  
    
    
    
 


  

   
  
  
   
   
 


}

  
  
  
  




</style>