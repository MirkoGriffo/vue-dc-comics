<template>
  <div id="app">
    
   <!-- Header -->
<Header />
   <!-- Main -->
<Topmain />
<Middlemain />
   <!-- Footer -->
   
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Topmain from "@/components/Topmain.vue";
import Middlemain from "@/components/Middlemain.vue";

export default {
  name: 'App',
  components: {
    Header,
    Topmain,
    Middlemain,
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
