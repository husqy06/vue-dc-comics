<template>
  <div id="app">
    <Header :navArray="navItem"/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import { navItem } from './data/data.js'

export default {
  name: 'App',
  data() {
    return {
      navItem
    }
  },
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">

</style>
