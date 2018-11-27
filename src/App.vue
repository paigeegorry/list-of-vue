<template>
  <div id="app">
    <List v-bind:cacti="cacti"/>
  </div>
</template>

<script>
import List from './components/List.vue';
import cacti from './cacti.js';

export default {
    data() {
        return {
            cacti
        };
    },
    components:{
        List,
    }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
