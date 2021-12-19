<template>
  <div id="app">
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './pages/Calculator';

export default {
  name: 'App',
  components: {
    Calculator
  }
}
</script>

<style>
body {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #fff;
  background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
