<template>
  <Header @changeTitle="ubahText" :text="text"/>
</template>

<script>
import Header from "@/components/Header.vue"
export default {
  name: 'App',
  components:{
    Header,
  },
  data(){
    return{
      text : "Ahlan Wa Sahlan, ini adalah text dari data binding"
    }
  },
  methods:{
    ubahText(newText){
      this.text = newText
    }
  }
  
}
</script>

<style>

</style>
