<template>
  <div id="app">
    <MyHeader/>

    <main>
      <myJumbotron/>
    </main>

    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'
import myJumbotron from './components/myJumbotron.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    myJumbotron,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
// importazione bootstrap
@import'~bootstrap/dist/css/bootstrap.css'
</style>
