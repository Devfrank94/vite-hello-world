  
<script>
export default {
  name: "AppTitle",
  components:{
    
  },
  data(){
    return{
      subTitle:'La mia prima app con Vite!'
    }
  }
}
</script>


<template>

  <h2>{{ subTitle }}</h2>

</template>


<style scoped>
  h2{
    color: red;
  }
</style>