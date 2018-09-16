
<template>
  <div class="app-wrapper">
    <app-banner></app-banner>
    <app-main></app-main>
    <!-- <Banner></Banner>
    <Main></Main> -->
  </div>
</template>

<script>
  import Banner from './components/Banner.vue';
  import Main from './components/Main.vue';

  export default {
    name: 'app',
    components: {
      'app-banner': Banner,
      'app-main': Main
    }
}
</script>


<style scoped>
  .app-wrapper {
    height: 100%;
    width: 100%;
  }
</style>