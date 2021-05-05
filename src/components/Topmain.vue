<template>
  <div class="jumbotron">
    <div class="container"></div>
  </div>
</template>

<script>
export default {
  name: "Topmain",
};
</script>

<style scoped>
.container {
  width: 1500px;
  margin: 0 auto;
}
.jumbotron {
  height: 400px;
  width: 100%;
  background-image: url("../assets/img/jumbotron.jpg");
  background-size: 100%;
  background-repeat: no-repeat;
}
.jumbotron h3 {
  color: #fff;
  font-size: 35px;
  padding-top: 50px;
}
</style>