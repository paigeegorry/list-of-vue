<template>
  <div id="app">
    <List v-bind:plants="plants"/>
  </div>
</template>

<script>
import List from './components/List';
import plants from './plants';

export default {
    data() {
        return {
            plants
        };
    },
    components:{
        List
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
