<template>
    <headerOne :title="title"/>
    <characterLibary/>

</template>

<script>
import headerOne from './components/headerOne.vue';
/*import footerOne from './components/footerOne.vue';
import assideOne from './components/assideOne.vue';*/
import characterLibary from './components/characterLibary.vue';

export default {
  name: 'App',
  components: {headerOne, characterLibary},
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
</style>
