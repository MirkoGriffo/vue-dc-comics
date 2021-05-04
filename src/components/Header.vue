<template>

<nav>
<img src="../assets/img/dc-logo.png" alt="logo">

<ul>
    <li><a href="#">characters</a></li>
    <li><a href="#">comics</a></li>
    <li><a href="#">movies</a></li>
    <li><a href="#">tv</a></li>
    <li><a href="#">games</a></li>
    <li><a href="#">collectibles</a></li>
    <li><a href="#">videos</a></li>
    <li><a href="#">fans</a></li>
    <li><a href="#">news</a></li>
    <li><a href="#">shop</a></li>
</ul>
</nav>
  
</template>

<script>
export default {
name: "Header",
}
</script>

<style scoped>
* {
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
nav {
    height: 250px;
    width: 100%;
    
    
}

nav img {
  
}

ul {
   display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  align-content: center;
}


ul li {
  
    list-style: none;
    text-transform: uppercase;
    padding: 15px;
    display: inline-block;
    position: relative;
    bottom: 100px;
   
   
   
}

ul li a {
    text-decoration: none;
    color: black;
}

ul li a:hover {
    color: blue;
}
</style>