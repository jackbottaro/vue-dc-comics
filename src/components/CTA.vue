<template>
<div>
<ul class="container">
  <li>
    <img src="../assets/buy-comics-digital-comics.png" alt="digital comics">
    <p>digital comics</p>
  </li>
  <li>
    <img src="../assets/buy-comics-merchandise.png" alt="dc merchandise">
    <p>dc merchandise</p>
  </li>
  <li>
    <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
    <p>subscription</p>
  </li>
  <li>
    <img src="../assets/buy-comics-shop-locator.png" alt="comic shop locator" id="locator">
    <p>comic shop locator</p>
  </li>
  <li>
    <img src="../assets/buy-dc-power-visa.svg" alt="dc power visa">
    <p>dc power visa</p>
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
  height: 120px;
  background-color: #0282f9;
  justify-content: center;
  display:flex;
}

h2{
  color: white;
}

ul{

  align-items: center;
  line-height: 120px;
  display: flex;
  justify-content: center;
  
}

li{
    flex-direction: row;
    display: flex;
    align-items: center;
    padding-right: 20px;


}

img{
  height: 100%;
  width: 40px;
  margin-right: 5px;
}

p{
  text-transform: uppercase;
  color: white;
  font-size: 13px;
}

#locator{
  width: 25px;
}

</style>
