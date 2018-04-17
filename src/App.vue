<template>
  <div id="app">
    <!--<div id="cover"></div>-->
    <headerArea></headerArea>
    <todo></todo>
    <footerArea></footerArea>
  </div>
</template>

<script>
  import  headerArea from './todo/headerArea'
  import  footerArea from './todo/footerArea'
  import  todo from './todo/todo'

  export default {
    name: 'App' ,
    components:{
      headerArea,
      footerArea,
      todo
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
  }
</style>
