<template>
  <div>
    <Pixel color="white" :current="color === 'white'" isInColorPicker />
    <Pixel color="lightblue" :current="color === 'lightblue'" isInColorPicker />
    <Pixel color="blue" :current="color === 'blue'" isInColorPicker />
    <Pixel color="darkblue" :current="color === 'darkblue'" isInColorPicker />
  </div>
</template>

<script>
import Pixel from './Pixel';

export default {
  name: 'ColorPicker',
  components: {
    Pixel
  },
  props: {
    color: String
  }
};
</script>