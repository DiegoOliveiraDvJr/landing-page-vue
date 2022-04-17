<template>
  <div>
    <Banner />
    <Footer />
  </div>
</template>

<script>
import Banner from './components/Banner.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Banner,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*{
  box-sizing: border-box;
  
}
body{
  margin: 0;
  padding:0;
  font-size: 16px;
}
</style>
