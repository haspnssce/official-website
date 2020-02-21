<template>
  <div id="app">
    <Navbar/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from '@/components/Navbar'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: { Navbar, Footer }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Ubuntu&display=swap');
@import url('https://fonts.googleapis.com/css?family=Roboto:100,100i,300,300i,400,400i,500,500i,700,700i,900,900i&display=swap');
html {
  font-size: 62.5%;
}
body {
  margin: 0;
  padding: 0;
}
#app {
  padding: 0;
  margin: 0;
}
</style>
