<template>
  <div id="app">
    
   <!-- Header -->
<Header />
   <!-- Main -->

   <!-- Footer -->
   
  </div>
</template>

<script>
import Header from "@/components/Header.vue";

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style lang="scss">
#app {
 width: 1500px;
    margin: 0 auto;
  
 
}

</style>
