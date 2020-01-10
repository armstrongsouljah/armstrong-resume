<template>
  <div id="app">
    <InformationCard/>
  </div>
</template>

<script>
import InformationCard from './components/InformationCard'

export default {
  name: 'app',
  components: {
    InformationCard
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
