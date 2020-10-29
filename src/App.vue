<template>
  <div id="app">
    <Navbar />
    <Jumbotron />
    <Overview />
    <Features />
    <Tech />
    <Page />
    <Contact />
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Jumbotron from './components/Jumbotron.vue'
import Overview from './components/Overview.vue'
import Features from './components/Features.vue'
import Tech from './components/Tech.vue'
import Page from './components/page.vue'
import Contact from './components/contact.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Jumbotron,
    Overview,
    Features,
    Tech,
    Page,
    Contact
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.icon{
  font-size: 100px;
}
.sansserif {
  font-family: sans-serif;
  font-size: 28px;
  font-weight: bold;
}
</style>
