<template>
  <section class="container mt-5">

    <div class="row justify-content-center">
        <div class="col-12 text-center">
            <img src="../assets/page-logo-1.png" alt="">
        </div>
        <div class="col-12 text-center">
            <h2>Inspired By Excellence & Innovation</h2>
        </div>
        <div class="col-12 text-secondary text-center">
            <span>We offer a wide range of high quality of teaching and extra-curricular activities.</span>
        </div>
        <div id="border" class="col-2"></div>
        <div class="col-12 mt-4">
            <div class="row justify-content-around align-items-center">
                <div class="col-7">
                    <h2>WHY CHOOSE AVADA UNIVERSITY?</h2>
                    <p class="text-secondary">We offer a range of training packages in a range of subject areas and can offer blended learning opportunities to best meet your needs. If sitting in a room with a trainer and having the opportunity for discussion with other learners sounds good to you then we can offer this. If you prefer to study in your own time and at your own speed then one of our world class facilities.</p>
                    <p class="text-secondary">If you prefer to study in your own time and at your own speed then one of our e-learning packages may be right up your street. There is a third option, which is you like the sound of both but perhaps can’t attend all training sessions, this is when blended learning comes into its own.</p>
                </div>
                <div class="col-4">
                    <button type="button" class="ltv-playbtn"></button>
                    <iframe allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" src="https://player.vimeo.com/video/80567526?autoplay=1" width="640" height="360" frameborder="0"></iframe>
                </div>
            </div>
        </div>
    </div>

  </section>
</template>

<script>
export default {
  name: 'myMainContent'
  
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


    #border{
        margin-top: 20px;
        border: 1px solid orange;
    }


</style>