<template>
  <div id="app">
    <RightEye />
    <LeftEye />
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
  * {
    margin: 0;
    padding: 0;
  }

  html {
    overflow: scroll;
    overflow-x: hidden;
    min-height: 100%;
    height: 100%;
  }

  html body {
    height: 100%;
  }

  #app {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: rgb(212, 212, 212);
  }

</style>
