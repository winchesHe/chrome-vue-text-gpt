<template>
  <div id="app">
    <layout />
  </div>
</template>

<script>
import Layout from './layouts/BasicLayout.vue'

export default {
  components: {
    Layout
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  width: 480px;
  height: 565px;
  font-family: Microsoft YaHei;
  color: #2c3e50;
}
</style>
