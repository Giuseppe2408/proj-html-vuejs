<template>
  <div id="app">
    <Myheader/>

    <main>

    </main>

    <Myfooter/>
  </div>
</template>

<script>
import Myheader from './components/Myheader.vue'
import Myfooter from './components/Myfooter.vue'

export default {
  name: 'App',
  components: {
    Myheader,
    Myfooter
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
