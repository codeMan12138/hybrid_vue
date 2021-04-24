<template>
    <div id="app">
        <img alt="Vue logo" src="./assets/logo.png" />
        <HelloWorld msg="Welcome to Your Vue.js App" />
        <h1>index222</h1>
        <div class="parent">
          parent
          <p class="son">son</p>
        </div>
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
    name: 'App',
    components: {
        HelloWorld,
    },
};
</script>

<style lang="scss">
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  .parent{
    width: 100px;
    height: 100px;
    background-color: red;
    .son{
      color: blue;
    }
  }
}
</style>
