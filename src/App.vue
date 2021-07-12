<template>
  <div id="app">
    <NavBar/>
    <Main/>
    <FooterIcon/>
    <FooterJumbo/>
    <FooterEnd/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Main from './components/Main.vue'
import FooterIcon from './components/FooterIcon.vue'
import FooterJumbo from './components/FooterJumbo.vue'
import FooterEnd from './components/FooterEnd.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Main,
    FooterIcon,
    FooterJumbo,
    FooterEnd,
  }
}
</script>

<style lang="scss">
@import "./style/app.scss"
</style>
