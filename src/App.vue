<template>
  <div id="app">
    <Checkbox v-model="value">
      hello world
    </Checkbox>
  </div>
</template>

<script>

import Checkbox from "./components/Checkbox";
export default {
  name: 'app',
  components: {
    Checkbox
  },
  data: function () {
    return {
      value: false
    }
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
