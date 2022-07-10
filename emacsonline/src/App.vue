<template>
<MainEditor/>
</template>

<script>
import MainEditor from './components/MainEditor.vue'

export default {
  name: 'App',
  components: {
    MainEditor
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
