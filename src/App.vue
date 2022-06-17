<template>
  <div id="app">
    <Myheader/>
  </div>
</template>

<script>
import Myheader from './components/Myheader.vue'

export default {
  name: 'App',
  components: {
    Myheader
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {

}
</style>
