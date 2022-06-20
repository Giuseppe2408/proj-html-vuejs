<template>
  <section class="container-fluid">
        <div class="row">
            <div id="course-img" class="carousel d-flex justify-content-center align-items-center col-4">
                <div class="row text-center justify-content-center">
                    <div class="col-12">
                        <h2>COURSES</h2>
                    </div>
                    <div class="col-2 border border-warning"></div>
                    <div class="col-12">
                        <span>View More</span>
                    </div>
                </div>
                
            </div>
            <div id="event-img" class="carousel d-flex justify-content-center align-items-center col-4">
                <div class="row text-center justify-content-center">
                    <div class="col-12">
                        <h2>EVENTS</h2>
                    </div>
                    <div class="col-2 border border-warning"></div>
                    <div class="col-12">
                        <span>View More</span>
                    </div>
                </div>
            </div>
            <div id="news-img" class="carousel d-flex justify-content-center align-items-center col-4">
                <div>
                    <div class="row text-center justify-content-center">
                        <div class="col-12">
                            <h2>LATEST NEW</h2>
                        </div>
                        <div class="col-2 border border-warning"></div>
                        <div class="col-12">
                            <span>View More</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
  </section>
</template>

<script>
export default {
  name: 'myCarousel'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .carousel{
        height: 650px; 
        color: white;
    }

    #course-img {
        background-image: url(../assets/home_courses_section_bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
    }
    #event-img {
        background-image: url(../assets/home_events_section_bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
    }
    #news-img {
        background-image: url(../assets/home_latest_news_section_bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
    }


</style>