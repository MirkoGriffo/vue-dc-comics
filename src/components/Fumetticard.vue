<template>
  <div class="box">
    <img :src="details.thumb" :alt="details.series" />
    <p>{{ details.series }}</p>
  </div>
</template>

<script>
export default {
  name: "Fumetticard",
  props: ["details"],
};
</script>

<style>
.box {
  flex-basis: calc(100% / 6 - 10px);
}
.box img {
  height: 80%;
  padding: 10px;
}

.box p {
  color: #fff;
  text-transform: uppercase;
}
</style>