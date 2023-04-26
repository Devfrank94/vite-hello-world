  
<script>
import AppTitle from "./components/AppTitle.vue"

export default {
  name: "App",
  components:{
    AppTitle
  },
  data(){
    return{
      title:'Vite Hello World'
    }
  }
}
</script>


<template>

  <h1>{{ title }}</h1>
  <AppTitle/>

</template>


<style scoped>
  h1{
    color: green;
  }
</style>