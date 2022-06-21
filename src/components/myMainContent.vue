<template>
    <div>
        <myVideo/>
        <whyStart/>
        <myCarousel/>
        <todayNews/>
        <signIn/>
    </div>
</template>

<script>
import myVideo from "./myVideo.vue";
import myCarousel from "./myCarousel.vue";
import whyStart from "./whyStart.vue";
import todayNews from "./todayNews.vue";
import signIn from "./signIn.vue";

export default {
  name: 'myMainContent',
  components : {
    myVideo,
    whyStart,
    myCarousel,
    todayNews,
    signIn
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

   

    h2{
        font-size: 40px;
    }
    p {
        font-size: 16px;
    }

    .background-grey{
        background-color: lightgrey;
    }

    

</style>