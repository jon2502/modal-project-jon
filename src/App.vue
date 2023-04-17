<template>
    <headerOne :title="title"/>
    <div id="asside">
      <characterLibary/>
      <assideOne/>
    </div>
    <footerOne/>
    

</template>

<script>
import headerOne from './components/headerOne.vue';
import footerOne from './components/footerOne.vue';
import assideOne from './components/assideOne.vue';
import characterLibary from './components/characterLibary.vue';

export default {
  name: 'App',
  components: {headerOne, characterLibary, assideOne, footerOne},
  data() {
    return {
      title: 'RPG Character Libary',
    }
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
  margin-top: 60px;
}
#asside{
  display: grid;
  grid-template-columns: 80vw 20vw
}
</style>
