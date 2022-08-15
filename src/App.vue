<template>
  <navbar></navbar>
  <image-field></image-field>
</template>

<script>
import Navbar from './components/Navbar.vue'
import ImageField from './components/Image.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    ImageField
  }
}
</script>

<style>
#app {
}
body{
  margin: 0;
  background-color: black;
}
</style>
