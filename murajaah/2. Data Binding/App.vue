
<template>
  <!-- <a v-bind:href="url"> Halaman VUEJS</a> -->
  <a :href="url"> Halaman VUEJS</a>
</template>

<script>

export default {
  name: 'App',
  data(){
    return {
        url : "https://v3.vuejs.org/",
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
