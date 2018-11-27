<template>
  <div id="app">
    <List 
      v-bind:plants="plants"
      v-bind:onSelect="handleSelect" />
  </div>
</template>

<script>
import List from './components/List';
import plants from './plants';

export default {
    data() {
        return {
            plants,
            selected: null
        };
    },
    components:{
        List
    },
    methods: {
        handleSelect(plant) {
            console.log('user selected cactus', plant.name);
        }
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
