<template>
  <div>
    <NavBar/>
    <div id="app" class="">
      <router-view/>
    </div>
  </div>
</template>

<script>

import NavBar from './components/navigation/NavBar'

export default {
  name: 'App',
  components: {
    NavBar
  }
}
</script>


<style>
@import './assets/css/main.css';

</style>
