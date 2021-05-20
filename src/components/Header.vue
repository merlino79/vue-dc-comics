<template>

<header class="cols container">

    <a href="/">
    <img src="../assets/img/dc-logo.png" alt="">
    </a>
    <ul>
      <li><a href="/">
        characters
      </a>
      </li>
      <li class="active">
        <a href="#">
        comics
      </a>
      </li>
      <li>
        <a href="/">
        Movies
      </a>
      </li>
      <li>
        <a href="/">
        tv
      </a>
      </li>
      <li>
        <a href="/">
        games
      </a>
      </li>
      <li>
        <a href="/">
        collectibles
      </a>
      </li>
      <li>
        <a href="/">
        videos
      </a>
      </li>
      <li>
        <a href="/">
        fans
      </a>
      </li>
      <li>
        <a href="/">
        news
      </a>
      </li>
      <li>
        <a href="/">
        shop
      </a>
      </li>
      
    </ul>

  
    
 </header>
  

 

  
</template>

<script>
export default {
  name: 'Header'

}
</script>

<style  lang="scss" scoped>
.cols{

  display: flex;
  height: 120px;
  width: 100%;
  ul{
    width: 100%;
    display: flex;
    justify-content: end;
    
    list-style: none;
  } 
  a{
    line-height: 120px;
    margin: 10px;
    text-decoration: none;
    color: #1E0000;
    
    
  } 
}
.active a{
  color: #0067F8;
}    
    
    
    
  
 
 
  
  
  
  
  
  
  
  








</style>