<template>  
  <div class="home bg-contrast-custom">
    <TutorEnv/>
  </div>
</template>

<script>

import TutorEnv from "../components/graph/TutorEnv"

export default {
  name: 'Home',
  components: {
    
    TutorEnv
  }
}
</script>

<style>
* {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0;
  padding:0;
  
}

body {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background-color: #932432;
}

header {
  width: 100vw;
  background-color: #eba487;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 0px 0px 5px 5px;
  -moz-border-radius: 0px 0px 5px 5px;
  -webkit-border-radius: 0px 0px 5px 5px;
  border: 0px solid #000000;
  -webkit-box-shadow: 1px 6px 5px 0px rgba(0,0,0,0.25);
  -moz-box-shadow: 1px 6px 5px 0px rgba(0,0,0,0.25);
  box-shadow: 1px 6px 5px 0px rgba(0,0,0,0.25);
}
.container {
    display: flex;
    width: 100%;
}

</style>
