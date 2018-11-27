<template>
    <ul>
        <li v-for="plant in plants"
            v-bind:key="plant.name"
            v-on:click="onSelect(plant)">
            <h3>{{plant.name}}</h3>
            <h4>{{plant.genus}}</h4>  
            <img v-bind:src="plant.image">  
        </li>
    </ul>
</template>

<script>
export default {

    props: {
        plants: Array,
        onSelect: Function
    }
};
</script>

<style>
   ul{
       list-style: none;
       text-align: center;
       display:flex;
       cursor:pointer;
   }
   h4{
       font-style: italic;
   }
   img {
       width: 90%;
   }
</style>
