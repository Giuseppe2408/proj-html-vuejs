<template>
    <div class="row justify-content-around align-items-center">
        <ul class="col-3">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2>{{item.subtitle}}</h2>
            <span>{{item.contact}}</span>
          </li>
        </ul>
        <ul class="col-3">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2>{{item.domandsubtitle}}</h2>
            <span>{{item.domand}}</span> 
            <div>{{item.date}}</div>
          </li>
        </ul>
        <ul class="col-3">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2>{{item.linkTitle}}</h2>
            <span>{{item.link1}}</span>
          </li>
        </ul>
        <ul class="col-3">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2>{{item.linkTitle1}}</h2>
            <span>{{item.link2}}</span>
          </li>
          
        </ul>
    </div>
  
</template>

<script>

export default {
  name: 'myFooterList',
  props: {
    linkFooter : Array
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  
</style>