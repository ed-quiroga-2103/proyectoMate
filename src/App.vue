<template>
  <div class="">
    <NavBar/>
    <div id="app" class="bg-dark-custom">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>

import NavBar from './components/navigation/NavBar'

export default {
  name: 'App',
  components: {
    NavBar
  },
  data(){
    return {
    }
  }
}
</script>


<style>
@import './assets/css/main.css';

body{
  background-color: #283747;
}

</style>
