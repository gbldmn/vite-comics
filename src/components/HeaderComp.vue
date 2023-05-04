<script>
export default{
    name: "HeaderComp"
}
</script>

<template>
     <header>
  <div>
  <img src="/img/dc-logo.png" alt="">
  </div>
  <div>
    <ul>
      <li> <a href="">characters</a> </li>
      <li> <a href="">comics</a> </li>
      <li> <a href="">movies</a> </li>
      <li> <a href="">tv</a> </li>
      <li> <a href="">games</a> </li>
      <li> <a href="">collectibles</a> </li>
      <li> <a href="">videos</a> </li>
      <li> <a href="">fans</a> </li>
      <li> <a href="">news</a> </li>
      <li> <a href="">shop</a> </li>
    </ul>
  </div>
 </header>

 <div class="img-big">
    <img src="/img/jumbotron.jpg" alt="">
 </div>
 
</template>

<style lang="scss" scoped>
 .img-big {
  width: 100%;
  height: 500px;
  img {
    width: 100%;
    height: 100%;
  }
 }
</style>