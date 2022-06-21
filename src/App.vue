<template>
  <div id="app">
    <MyHeader/>

    <main>
      <myJumbotron/>
      <myMainContent/>
    </main>

    <MyFooter/>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyFooter from './components/MyFooter.vue'
import myJumbotron from './components/myJumbotron.vue'
import myMainContent from './components/myMainContent.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    myJumbotron,
    myMainContent,
  },
 
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
// importazione bootstrap
ul li {
    list-style: none;
      a{
        text-decoration: none;
        color: black;
      }
    }
  
</style>
