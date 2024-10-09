<template>
  <div>
    <button @click="mostrar">mostrar api 1</button>
    <p></p>
  </div>
  <div>
    <button @click="mostrar2">mostrar api 2</button>
    <p></p>
  </div>
  <div>
    <button @click="mostrar3">mostrar api 3</button>
    <p></p>
  </div>
  <div>
    <button @click="mostrar4">mostrar api 4</button>
    <p></p>
  </div>
  
  
</template>

<script setup>
  

  const api1 = "https://countriesnow.space/api/v0.1/countries/population"
  const api2 = "https://api.jikan.moe/v4/recommendations/anime"
  const api3 = "https://api.jikan.moe/v4/random/anime"
  const api4 = "https://api.jikan.moe/v4/random/manga"

  const mostrar = () =>{
    return console.log(api1);
  }
  const mostrar2 = () =>{
    return console.log(api2);
  }
  const mostrar3 = () =>{
    return console.log(api3);
  }
  const mostrar4 = () =>{
    return console.log(api4);
  }


</script>

<style>

</style>
