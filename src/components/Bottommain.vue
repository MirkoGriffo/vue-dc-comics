<template>
  <div class="blu">
<div class="container">
    <ul>
        <li> <img src="../assets/img/buy-comics-digital-comics.png"> <p>digital comics</p>
        </li>
        <li><img src="../assets/img/buy-comics-merchandise.png"> <p>dc merchandise</p></li>
        <li><img src="../assets/img/buy-comics-subscriptions.png"> <p>subscription</p></li>
        <li><img src="../assets/img/buy-comics-shop-locator.png"> <p>comic shop locator</p></li>
        <li><img src="../assets/img/buy-dc-power-visa.svg"> <p>dc power visa</p></li>
    </ul>
   
</div>
  </div>
</template>

<script>
export default {
    name: "Bottommain"
}
</script>

<style scoped>
.blu {
    height: 170px;
    width: 100%;
    background-color: #0282f9;
      display: flex;
  flex-wrap: wrap;
  flex-direction: row;
  justify-content: flex-start;
  align-items: auto;
  align-content: center;
}
.container {
     width: 1500px;
    margin: 0 auto;
    
}
ul li {
padding-left: 25px;
}
ul li,
ul p {
    list-style: none;
    display: inline-block;
   color: #fff;
    text-transform: uppercase;
    font-size: 15px;
    
   
   
}
ul li img {
    width: 18%
    
    
    }
    ul li p {
        position: relative;
        bottom: 20px;
        margin-left: 8px;
    }
</style>