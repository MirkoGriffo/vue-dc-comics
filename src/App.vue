<template>
  <div id="app">
    
   <!-- Header -->
<Header />
   <!-- Main -->
<Topmain />
<Listafumetti />
<Bottommain />
   <!-- Footer -->
   
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Topmain from "@/components/Topmain.vue";
import Listafumetti from "@/components/Listafumetti.vue";
import Bottommain from "@/components/Bottommain.vue";


export default {
  name: 'App',
  components: {
    Header,
    Topmain,
    Listafumetti,
    Bottommain,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {

  
 
}

</style>
