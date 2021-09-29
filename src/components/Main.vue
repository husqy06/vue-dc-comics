<template>
  <main>
    <section class="jumbotron"></section>

    <SeriesList />

    <section class="main-bottom">
      <div class="main-bottom-container">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png">
          <span>digital comics</span>
        </div>
        <div>
          <img src="../assets/img/buy-comics-merchandise.png">
          <span>dc merchandise</span>
        </div>
        <div>
          <img src="../assets/img/buy-comics-subscriptions.png">
          <span>subscriptions</span>
        </div>
        <div>
          <img src="../assets/img/buy-comics-shop-locator.png">
          <span>comic shop locator</span>
        </div>
        <div>
          <img src="../assets/img/buy-dc-power-visa.svg">
          <span>dc power visa</span>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
import SeriesList from './SeriesList.vue'

export default {
  name: 'Main',
  components: {
    SeriesList
  },
  data() {
    return {
   
    }
  }
}
</script>

<style scoped lang="scss">

@import '../style/style.scss';

</style>
