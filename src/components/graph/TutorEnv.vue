<template>
  <div>
    <mainGraph/>
  </div>
</template>

<script>

import mainGraph from './mainGraph.vue'

export default {
  name: 'TutorEnv',
  props: {
    msg: String
  },
  components: {
        mainGraph
    },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
