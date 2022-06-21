<template>
    <div class="row">
        
            <blockFooter 
            v-for="(block, i) in linkFooter"
            :key="i"
            :footerBlock="block"/>
          
    </div>
  
</template>

<script>
import blockFooter from "./blockFooter.vue";
export default {
  name: 'myFooterList',
  components : {
    blockFooter
  },
  props: {
    linkFooter : Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>