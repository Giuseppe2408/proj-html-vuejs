<template>
    <div class="col-2">
        <ul>

          <li>
            <h2>{{footerBlock.subtitle}}</h2>
            <a href="">
              <span>{{footerBlock.text}}</span>
            </a>
          </li>
          
        </ul>
    </div>    
    
</template>

<script>
export default {
  name: 'blockFooter',
  props : {
    footerBlock : Object
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>