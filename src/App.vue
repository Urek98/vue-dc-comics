<template>
  <div id="app">
    <NavBar/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Main,
    Footer,
  }
}
</script>

<style lang="scss">
// importare il nostro scss generico.
@import "./style/app.scss"
</style>
