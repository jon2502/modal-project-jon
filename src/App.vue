<template>
    <headerOne :title="title" @toggle="ToggleBtn"/>
    <div id="asside">
      <characterLibary v-if="indicator == 'a'"/>
      <ToggleBrandr v-if="indicator == 'b'"/>
      <ToggleGethlire v-if="indicator == 'c'"/>
      <assideOne/>
    </div>
    <footerOne/>
</template>

<script>
import headerOne from './components/headerOne.vue';
import footerOne from './components/footerOne.vue';
import assideOne from './components/assideOne.vue';
import characterLibary from './components/characterLibary.vue';
import ToggleBrandr from './components/ToggleBrandr.vue';
import ToggleGethlire from './components/ToggleGethlire.vue'

export default {
  name: 'App',
  components: {headerOne, characterLibary, assideOne, footerOne, ToggleBrandr, ToggleGethlire},
  data() {
    return {
      title: 'RPG Character Libary',
      indicator: "a"    
    }
  },
  methods: {
    ToggleBtn(id){
      this.indicator = id
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  min-height: 100vh;
}
#asside{
  display: grid;
  grid-template-columns: 80% 20%
}
</style>
