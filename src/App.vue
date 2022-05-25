<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search...">
      </div>
    </main>
  </div>
</template>

<script>
export default {
name: 'app',
data() {
  return{
    api_key: 'ef531f2f35d70e4821f0dca6b2137316'
  }
}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body{
  font-family: 'Montserrat', sans-serif;
}
#app{
  background-image: url('./assets/cold.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}
main{
  min-height: 100vh;
  padding: 25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75)) ;
}
</style>