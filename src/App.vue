<template>
  <div id="app">

  Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sed facilis blanditiis eaque eum iusto ipsum tempore facere quos, voluptas omnis, error officia minus distinctio vitae quibusdam hic animi illum. Architecto.

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



    axios('/doodle/result.json')
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
