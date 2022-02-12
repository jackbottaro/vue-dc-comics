<template>
<div>
  <div class="container">

<div class="cards">
      <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
    <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
    <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
    <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
    <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
    <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
    <div class="card">
      <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
      <span>ciao</span>
    </div>
</div>

  </div>

  <button>LOAD MORE</button>

</div>
 
</template>

<script>
export default {
	name: "Main"
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">


div{
  display: flex;
  align-items: center;
  flex-direction: column;
}

.cards{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  flex-direction: row;
}

h2{
  color: white;
}

span{
  color: white;
  text-transform: uppercase;
text-align: start;
}

.card{
  display: flex;
  flex-direction: column;
  margin: 20px;
  margin-top: 40px;

}

img{
  height: 200px;

  margin-bottom: 20px;
}

button{
  background-color: #0282f9;
  padding: 10px 40px;
  color: white;
  font-weight: bold;
  margin: 20px;
  border: 1px solid #0282f9;
  cursor: pointer;
}
</style>
