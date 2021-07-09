<template>
  <div id="app">
    <ColorPicker />
    <Canvas />
  </div>
</template>

<script>
import Canvas from './components/Canvas';
import ColorPicker from './components/ColorPicker.vue';

export default {
  name: 'app',
  components: {
    Canvas,
    ColorPicker
  }
};
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
