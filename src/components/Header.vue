<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="">

    <ul>
      <li v-for="(item, index) in navArray" :key="index">
        <a :href="item.href" :class="item.href == true ? 'itemActive':''">{{ item.text }}</a>
      </li>
    </ul>
  </header>
</template>

<script>

export default {
  name: 'Header',
  props: ['navArray'],
}
</script>

<style scoped lang="scss">

@import '../style/style.scss';

</style>
