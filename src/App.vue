<template>
  <div id="app">
    <NavBar/>
    <Main/>
    <FooterIcon/>
    <FooterJumbo/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Main from './components/Main.vue'
import FooterIcon from './components/FooterIcon.vue'
import FooterJumbo from './components/FooterJumbo.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Main,
    FooterIcon,
    FooterJumbo,
  }
}
</script>

<style lang="scss">
// importare il nostro scss generico.
@import "./style/app.scss"
</style>
