<template>
<div class="cols">
  <div class="container">
    <div class="btn">
      <button class="bottone">
        <a href="#">
     
            SIGN-UP NOW!
   
        </a>
      </button>

    </div>
    <div class="follow">
      <ul>
        <li>
      
           <a href="#">FOLLOW US</a>
     
      </li>
       <li>
      
           <a href="#">
             <img src="../assets/img/footer-facebook.png" alt="facebook">
           </a>
     
      </li>
       <li>
      
           <a href="#">
             <img src="../assets/img/footer-twitter.png" alt="twitter">
           </a>
     
      </li>
       <li>
      
           <a href="#">
              <img src="../assets/img/footer-youtube.png" alt="youtube">
           </a>
     
      </li>
       <li>
      
           <a href="#">
             <img src="../assets/img/footer-pinterest.png" alt="pinterest">
            
           </a>
     
      </li>
       <li>
      
           <a href="#">
             <img src="../assets/img/footer-periscope.png" alt="periscope">
           </a>
     
      </li>
      </ul>
     
     
      

    </div>
  </div>
 

</div>
  
</template>

<script>
export default {
  name: 'FooterBotton'

}
</script>

<style lang="scss" scoped>
.cols{

  width: 100%;
  height: 120px;
  line-height: 120px;
   background-color: #303030;

.btn{
  float: left;
  .bottone{
    padding: 15px;
    
    background: #303030;
    border: 3px solid  #1278E3;
    cursor: pointer;
    a{
       color: white;
    }
  }
  
}
.follow{
  float: right;
  a{
    text-transform: uppercase;
    color: #0067F8;
    font-size: 2rem;
  }
  img{
    padding: 10px;
    margin: 10px;
    margin-top: 25px;
  }
}


}

</style>


