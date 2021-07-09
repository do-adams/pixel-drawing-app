<template>
  <div>
    <Pixel color="white" :current="color === 'white'" />
    <Pixel color="lightblue" :current="color === 'lightblue'" />
    <Pixel color="blue" :current="color === 'blue'" />
    <Pixel color="darkblue" :current="color === 'darkblue'" />
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