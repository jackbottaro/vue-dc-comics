<template>
<div>
  <div id="container">

    <div>
      <ul>
        <h3>dc comics</h3>
        <li><a href="#">Characters</a></li>
        <li><a href="#">Comics</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">Games</a></li>
        <li><a href="#">Videos</a></li>
        <li><a href="#">News</a></li>
      </ul>

      <ul>
        <h3>shop</h3>
        <li><a href="#">Shop DC</a></li>
        <li><a href="#">Shop DC collectibles</a></li>
      </ul>
    </div>

    <div>
      <ul>
        <h3>dc</h3>
        <li><a href="#">Terms Of Use</a></li>
        <li><a href="#">Privacy policy(New)</a></li>
        <li><a href="#">Ad Choice</a></li>
        <li><a href="#">Advertising</a></li>
        <li><a href="#">Jobs</a></li>
        <li><a href="#">Subscriptions</a></li>
        <li><a href="#">Talent Workshops</a></li>
        <li><a href="#">CSPC Certificates</a></li>
        <li><a href="#">Ratings</a></li>
        <li><a href="#">Shop Help</a></li>
        <li><a href="#">Contact US</a></li>
      </ul>


    </div>

    <div>
      <ul>
        <h3>sites</h3>
        <li><a href="#">DC</a></li>
        <li><a href="#">MAD Magazine</a></li>
        <li><a href="#">DC Kids</a></li>
        <li><a href="#">DC Universe</a></li>
        <li><a href="#">DC Power Visa</a></li>
      </ul>
    </div>
  </div>

  <div id="social-bar">
    <a href="#" id="newsletter-cta">SIGN-UP NOW!</a>


    <div id="social-links">
      <p>FOLLOW US</p>
      <img src="../assets/footer-facebook.png" alt="Facebook Logo">
      <img src="../assets/footer-twitter.png" alt="Twitter Logo">
      <img src="../assets/footer-youtube.png" alt="Youtube Logo">
      <img src="../assets/footer-pinterest.png" alt="Pinterest Logo">
      <img src="../assets/footer-periscope.png" alt="Periscope Logo">
    </div>

  </div>

</div>


 
</template>

<script>
export default {
  name: "Footer",
  props: {
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#container{
  background-image: url("../assets/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height: 400px;
  display: flex;
}

#social-bar{
  background-color: #303030;
  height: 100px;
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

#social-links{
  display: flex;
  flex-direction: row;
   align-items: center;
}

#newsletter-cta{
  padding: 15px;
  border: 1px solid #0282f9;
}

p{
  color: #0282f9;
  font-weight: bold;
  margin-right: 20px;
  font-size: 1.17em;
}

h3{
  text-transform: uppercase;
  padding-bottom: 15px;
}

a{
  text-decoration: none;
  font-weight: lighter;
}

h3,
a{
  color: white;
}

ul{
  padding: 20px;
}

img {
  height: 60px;
  padding: 10px;
    
}
</style>
