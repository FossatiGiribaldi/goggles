<template>
  <div id="app">

   Lorem ipsum

  </div>
</template>


<script>
import axios from 'axios';

export default {
  data() {
    return {

    }
  },
  mounted() {



    axios('doodle/result.json')
      .then(res => {
        console.log(res);
      })
  }
}
</script>

<style lang="scss">
#app {
  font-size: 2em;
}
</style>
