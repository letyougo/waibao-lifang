<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import top from './components/top'
import middle from './components/middle.vue'
import bottom from './components/bottom.vue'
import panel from './components/float.vue'
export default {
  name: 'app',
  components: {
      top,middle,bottom,panel
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
  color: #2c3e50;
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
}
  li{
    list-style: none;
  }
</style>
