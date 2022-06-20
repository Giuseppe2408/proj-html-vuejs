<template>
  <section class="container-fluid">
    <div class="container py-5">
        <div class="row justify-content-center">
        <div class="col-12 text-center">
            <img src="../assets/page-logo-1.png" alt="">
        </div>
        <div class="col-12 text-center">
            <h2>Today’s Univeristy News</h2>
        </div>
        <div class="col-12 text-center">
            <span>Covering topics from classes to politics and student organization events.</span>
        </div>
        <div class="col-2 my-3 border border-warning"></div>
        <!-- parte img -->
        <div class="col-12">
            <div class="row justify-content-center">
                <div class="col-3">
                    <img src="../assets/news_single_post_header_1.jpg" alt="">
                    <div class="bg-white row justify-content-between">
                        <div class="col-12">
                            <h2>What do successful grads think you should study?</h2>
                        </div>
                        <div class="col-12">
                            <span>By <span>admin</span>|March 16th, 2016</span>
                        </div>
                        <div class="col-4">
                            <span>Read More</span>
                        </div>
                        <div class="col-1"><span>0</span></div>
                    </div>
                </div>
                <div class="col-3">
                    <img src="../assets/news_single_post_header_2.jpg" alt="">
                </div>
                <div class="col-3">
                    <img src="../assets/news_single_post_header_3.jpg" alt="">
                </div>
            </div>
        </div>
    </div>
    </div>
    
  </section>
</template>

<script>
export default {
  name: 'todayNews'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    section{
        background-color: #e6e6e6;
        img{
        max-width: 100%;
        object-fit: contain;
    }
    }
</style>