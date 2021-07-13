<template>
  <div id="app">
    <NavBar/>
    <Main :comics="comics"/>
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
import comicsJson from './jsons/dc-comics.json';

export default {
  name: 'App',
  components: {
    NavBar,
    Main,
    FooterIcon,
    FooterJumbo,
    FooterEnd,
  },
  data: function() {
    return {
      comics: comicsJson,
    };
  },
}
</script>

<style lang="scss">
@import "./style/app.scss"
</style>
