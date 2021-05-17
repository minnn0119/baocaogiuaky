<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Hello/>
    <Vd1/>
    <br>
    <Vd2/>
    <br>
    <Vd3/>
    <br>
    <Vd4/>
    <br>
    <Vd5/>
    <br>
    <Node/>
  </div>
</template>

<script>
import Hello from './components/Hello'
import Vd1 from './components/Vd1'
import Vd2 from './components/Vd2'
import Vd3 from './components/Vd3'
import Vd4 from './components/Vd4'
import Vd5 from './components/Vd5'
import Node from './components/Node'


export default {
  name: 'App',
  components: {
    Hello,
    Vd1,
    Vd2,
    Vd3,
    Vd4,
    Vd5,
    Node
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
