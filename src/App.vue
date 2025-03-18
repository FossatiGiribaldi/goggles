<template>
  <div id="app">

  Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis ipsa et nemo error numquam, assumenda atque ex vitae, dolorem praesentium quo unde veniam, perferendis fugit. A sint porro quae. Iusto.

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



    axios('../doodle/result.json')
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
