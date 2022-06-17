<template>
  <div class="container-fluid">
    <div class="row">
        <div class="col-12 justify-content-center align-items-center" id="jumbo">
            <div class="container">

                <div class="row">
                        <div class="col-12">
                        <h1>Inspirings Tomorrows Leader</h1>
                    </div>
                    <div class="col-12">
                        <h2>The Future Belongs To Those Who See Possibilities Today</h2>
                    </div>
                    <div class="col-12">
                        <div class="row">
                            <div class="col-3">
                                <button>FIND A COURSE</button>
                            </div>
                            <div class="col-3">
                                <button>APPLY NOW</button>
                            </div>
                        </div>                 
                    </div>
                </div>
                
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'myJumbotron'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    #jumbo{
        background-image: url(../assets/home_main_slider_bg.jpg);
        height: 700px;
        background-position: center;
        background-size: cover;
        color: white;
    }
</style>