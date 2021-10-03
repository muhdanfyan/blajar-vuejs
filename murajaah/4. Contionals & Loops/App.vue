<template>
<div v-if="products.length">
  <ul>
    <li v-for="item in products" :key="item.id">
      {{ item.title }} - {{ item.price }}
    </li>
  </ul>
</div>
<div v-else>
  <p>No Data</p>
</div>
</template>

<script>

export default {
  name: 'App',
  data(){
    return {
        nama : "Joko",
        products:[
          {id:1, title:"Product 1", price:3000},
          {id:2, title:"Product 2", price:5000},
          {id:3, title:"Product 3", price:7000},
          {id:4, title:"Product 4", price:2000},
          {id:5, title:"Product 5", price:2500},
        ]
      }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>