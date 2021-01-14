<template>
  <div id="nav">
    <Navbar />
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  max-width: 600px;
  margin: auto;
  color: #2c3e50;

}
body{
  background-color: antiquewhite;
}

</style>

<script>
import Navbar from './components/Navbar'
export default {
  components: {
    Navbar
  }
}
</script>
