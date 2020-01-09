<template>
  <div id="app">
    <InformationCard/>
    <Contact/>
  </div>
</template>

<script>
import InformationCard from './components/InformationCard';
import Contact from './components/Contact';

export default {
  name: 'app',
  components: {
    InformationCard,
    Contact
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
