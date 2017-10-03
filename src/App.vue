<template>
<div>
  <h1>{{titulo}}</h1>
  <ul>
    <li v-for="foto in fotos">
        <img :src="foto.url" :alt="foto.titulo" />
    </li>
  </ul>
  
  </div>
</template>

<script>
  export default {
    data() {
      return {
        titulo:"AluraPIC",
        fotos:[
          {
            url:'http://tudosobrecachorros.com.br/wp-content/uploads/como-fazer-seu-cachorro-feliz-1024x686.jpg',
            titulo:'Cachorro'
        },
        {
          url:'http://tudosobrecachorros.com.br/wp-content/uploads/como-fazer-seu-cachorro-feliz-1024x686.jpg',
          titulo:'Cachorrão'
        }]
      }
    }
  }
</script>

<style>

</style>
