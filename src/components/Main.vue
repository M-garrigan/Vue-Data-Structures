<template>
  <div class="body">
     <dataStructs></dataStructs>
  </div>
</template>

<script>
  import DataStructs from './DataStructs.vue';

  export default {
    name: 'Main',
    components: {
      'dataStructs': DataStructs
    }
  }
</script>

<style scoped>
  .body {
    background: rgb(228, 226, 226);
    height: 200vh;
  }
</style>

