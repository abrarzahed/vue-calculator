<template>
<h1> Calculator App <br> vue.js  <br> Css grid</h1>
  <Calculator/>
  <span>Note: This is a demo calculator app. So functionality are not 100% accurate.😒</span>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
    Calculator
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
}
</style>
