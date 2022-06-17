<template>
  <div class="container-fluid">
    <div class="row">
        <div class="col-12" id="jumbo">
            <div class="container d-flex h-100">

                <div class="row justify-content-center align-self-center">
                        <div class="col-12">
                        <h1 class="text-center">Inspirings Tomorrows Leader</h1>
                    </div>
                    <div class="col-12">
                        <h2 class="text-center">The Future Belongs To Those Who See Possibilities Today</h2>
                    </div>
                    <div class="col-6 mt-2">
                        <div class="row justify-content-center">
                            <div class="col-3">
                                <button class="orange-button">FIND A COURSE</button>
                            </div>
                            <div class="col-3">
                                <button id="azure-button">APPLY NOW</button>
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
        h1{
            font-size: 70px;
        }
        h2{
            font-size: 30px;
        }
        .orange-button{
            width: 100%;
            background-color: #ffab0b;
            border: 1px solid #ffab0b;
            padding: 5px;
        }
        #azure-button{
            width: 100%;
            background-color: #77e6fe;
            border: 1px solid #77e6fe;
            padding: 5px;
        }
        
    }
</style>