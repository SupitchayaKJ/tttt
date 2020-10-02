<template>
<div id="app">
    <img alt="Vue logo" src="./assets/opp.png">
    <!--<HelloWorld msg="Welcome to The Anime" />-->
    <music />
</div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
//import Anime from './components/Anime'
import music from './components/music.vue'
export default {
    name: 'App',
    components: {
        //HelloWorld,
        //Anime
        // eslint-disable-next-line vue/no-unused-components
        music,
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
