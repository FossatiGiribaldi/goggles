<template>
  <div id="app">

    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nostrum doloribus praesentium tempora sint? Non aut, natus
    sequi iure inventore iste dolorum ab modi voluptate quaerat ea, neque harum earum asperiores.

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


    axios('/doodle/result.json').then(res => {
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
