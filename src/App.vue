
<template>
  <div id="app">
    <template class="container">
      <nav>
        <div
          class="nav-wrapper purple darken-4
"
        >
          <a href="#" class="brand-logo right">Armstrong</a>
          <ul id="nav-mobile" class="left hide-on-med-and-down">
            <li><a href="sass.html">About</a></li>
            <li><a href="badges.html">Portfolio</a></li>
            <li><a href="collapsible.html">Contact</a></li>
          </ul>
        </div>
      </nav>
    </template>
    <Intro />
    <InformationCard />
    <Contact />
  </div>
</template>

<script>
import InformationCard from "./components/InformationCard";
import Contact from "./components/Contact";
import Intro from './components/Intro';

export default {
  name: "app",
  components: {
    InformationCard,
    Contact,
    Intro
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
