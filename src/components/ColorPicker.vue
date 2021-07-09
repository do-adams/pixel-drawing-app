<template>
  <div>
    <Pixel color="white" :current="color === 'white'" interactive />
    <Pixel color="lightblue" :current="color === 'lightblue'" interactive />
    <Pixel color="blue" :current="color === 'blue'" interactive />
    <Pixel color="darkblue" :current="color === 'darkblue'" interactive />
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