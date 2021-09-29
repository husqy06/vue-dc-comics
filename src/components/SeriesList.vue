<template>
  <section class="series-container">
    <span class="series-container-title">current series</span>
    <ul>
      <li v-for="(item, index) in seriesItem" :key="index" class="serie-card">
        <img :src="item.thumb" alt="">
        <span class="card-title">{{ item.series }}</span>
      </li>
    </ul>
    <div class="botton-container"><span class="botton-series">load more</span></div>
  </section>
</template>

<script>
import { seriesItem } from '../data/data.js'

export default {
  name: 'SeriesList',
  data() {
    return {
      seriesItem
    }
  }
}
</script>

<style scoped lang="scss">

@import '../style/style.scss';

</style>
