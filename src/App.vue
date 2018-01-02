<template>
  <div id="app">
    <cloud-head/>
    <router-view/>
  </div>
</template>

<script>
import header from '@/components/common/header'
export default {
  name: 'app',
  components : {
    cloudHead : header
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
