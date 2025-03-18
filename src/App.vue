<template>
  <div id="app">

   Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda delectus tempora sed beatae, voluptate, iure id sapiente consequatur obcaecati officia cupiditate eos vitae dolorum modi vel voluptatum totam doloremque error.

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
