<template>

  <div id="row">
    <div class="container">
      <div class="logo">
        <img src="../assets/dc-logo.png" alt="">
      </div>
      <div class="nav">
        <ul>
          <li>characters</li>
          <li class="active">comics</li>
          <li>movies</li>
          <li>tv</li>
          <li>games</li>
          <li>collectibles</li>
          <li>videos</li>
          <li>fan</li>
          <li>news</li>
          <li>shop</li>
        </ul>
      </div>
    </div>


  </div>


 
</template>

<script>
export default {
  name: "Header",
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

#row{
  background-color: white;
  height: 100px;
  display: flex;
  flex-direction: row;
  justify-content: center;
}

.logo{
width: 30%;
align-items: center;
    display: flex;

}

.nav{
    margin: 0 auto;
}

ul{
  display: flex;
  height: 100%;
  align-items: center;
  align-content: center;
}

li{
  padding: 0 20px;
  list-style-type: none;
  text-transform: uppercase;
font-weight: bold;
font-size: 0.8rem;
cursor: pointer;
}

.active{
  color: #0282f9;
}

img{
  height: 70px;

}

</style>
