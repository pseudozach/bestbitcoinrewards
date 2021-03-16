<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <div>
      <img alt="logo" src="./assets/percentage.png">
      <h1>Best Bitcoin Rewards</h1>
      <p>Comparison of all Bitcoin cashback rewards sites and apps. Searchable and (mostly) up to date.</p>
    </div>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Table/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Table from './components/table.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    Table
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
