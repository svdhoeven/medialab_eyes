<template>
  <div id="app" class="eyes begging">
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

  .eyes {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    background: blue;
  }

  .eyes section{
    width: 50%;
    height: 100%;
    background-size: 500px 500px;
    background-position: center;
    background-repeat: no-repeat;
  }

</style>
