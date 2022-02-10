<template>
<div>
<ul>
  <li>
    <img src="../assets/buy-comics-digital-comics.png" alt="">
    <p>digital comics</p>
  </li>
  <li>
    <img src="../assets/buy-comics-digital-comics.png" alt="">
    <p>digital comics</p>
  </li>
  <li>
    <img src="../assets/buy-comics-digital-comics.png" alt="">
    <p>digital comics</p>
  </li>
  <li>
    <img src="../assets/buy-comics-digital-comics.png" alt="">
    <p>digital comics</p>
  </li>
  <li>
    <img src="../assets/buy-comics-digital-comics.png" alt="">
    <p>digital comics</p>
  </li>
</ul>
</div>
 
</template>

<script>
export default {
  name: "CTA",
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div{
  padding: 80px;
  background-color: #0282f9;;
}

h2{
  color: white;
}

ul{
  display: flex;
  justify-content: space-around;
}

li{
    flex-direction: row;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

img{
  height: 100%;
  width: 50px;
  margin-right: 20px;
}

p{
  text-transform: uppercase;
  color: white;
}

</style>
