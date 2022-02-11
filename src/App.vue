<template>
  <div id="app">
    <Menu/>
    <Accueil/>
    <Apropos/>
    <footerPage /> 
  </div>
</template>

<script>
import Menu from './components/Menu'
import Accueil from './components/Accueil'
//import MentionsLegales from './components/MentionsLegales'
import Apropos from './components/Apropos'
import footerPage from './components/footerPage'

export default {
  name: 'App',
  components: {
    Menu,
    Accueil,
   // MentionsLegales,
    Apropos,
    footerPage,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
