<template>
  <div class="flex-wrapper">
    <div class="structs" v-for="item in items">
      <h3>{{item.title}}</h3>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'DataStructs',
    data () {
      return {
        items: [
          {title: 'Linked List'},
          {title: 'Arrays'},
          {title: 'Hash Table'},
          {title: 'Trees'},
          {title: 'Graphs'},
          {title: 'Networks'},
          {title: 'Stack'},
          {title: 'Queue'}
        ]
      }
    }
  }
</script>

<style scoped>
  .flex-wrapper {
    align-items: flex-start;
    display: flex; 
    flex-wrap: wrap;
    height: 100%;
    justify-content: space-evenly;
    width: 100%;
  }
  .structs {
    background: rgb(248, 194, 93);
    border-radius: 10px;
    box-shadow: 2px 2px 2px gray;
    height: 200px;
    margin: 20px;
    text-align: center;
    width: 150px;
  }
</style>
