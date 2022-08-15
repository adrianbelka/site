<template>
<nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="#">ADRIAN BELKA</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <a class="nav-item" href="#">O MNIE</a>
      <a class="nav-item" href="#">KONTAKT</a>
    </div>
  </div>
</nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.navbar{
  background-color: black;
  border-bottom: 1px solid white;
  color: white;
  display: flex;
  align-content: center;
  margin: 2rem;
  font-size: 1rem;
  font-family: 'Dosis', sans-serif;
}
.navbar-collapse{
  justify-content:flex-end;
}
.navbar-nav{
  width: 30%;
  justify-content: space-around;
  
}
.navbar a{
  text-decoration: none;
  color: white;
}
</style>
