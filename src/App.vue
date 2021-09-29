<template>
  <div id="app">
    <Header :navArray="navItem"/>
    <Main/>
  </div>
</template>

<script>
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
    Main
  }
}
</script>

<style lang="scss">

</style>
