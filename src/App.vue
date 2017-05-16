<template>
  <div id="app">
    <LeftEye />
    <RightEye />
  </div>
</template>

<script>
import LeftEye from './components/LeftEye';
import RightEye from './components/RightEye';

export default {
  name: 'app',
  components: {
    LeftEye, RightEye
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
