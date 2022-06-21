<template>
    <div class="row justify-content-around align-items-center ">
        <ul class="col-2">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2>{{item.subtitle}}</h2>
            <span>
              {{item.contact}}
            </span>
          </li>
        </ul>
        <ul class="col-2">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2>{{item.domandsubtitle}}</h2>
            <span>{{item.domand}}</span> 
            <div class="color-grey">{{item.date}}</div>
          </li>
        </ul>
        <ul class="col-2">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2 class="my-3">{{item.linkTitle}}</h2>
            <span>{{item.link1}}</span>
          </li>
        </ul>
        <ul class="col-2">
          
          <li v-for="(item,i) in linkFooter" :key="i">
            <h2 class="my-3">{{item.linkTitle1}}</h2>
            <span>{{item.link2}}</span>
          </li>
          
        </ul>
        <ul class="col-2 mb-5">
          <li v-for="(item,i) in linkFooter " :key="i">
            <div class="row">
              <div class="col-3">
                <div :class="item.calendario">
                  <span class="color-orange">{{item.num}}</span>
                </div>
              </div>
              <div class="col-8">
                    <h2>{{item.eventsTitle}}</h2>
                    <strong>{{item.text}}</strong>
                    <div class="color-grey">{{item.dataevent}}</div>
                    <div class="color-grey">{{item.location}}</div>
              </div>
            </div>            
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
  .color-grey{
    color: grey;
  }
  .calendario {
    padding: 20px;
    background-color: lightgrey;
    border: 1px solid orange;
    border-bottom: 30px solid orange;
    
    .color-orange{
      color: orange;
    }
    
  }
</style>