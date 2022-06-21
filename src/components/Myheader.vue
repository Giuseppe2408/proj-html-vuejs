<template>
  <header>
    <div class="container-fluid">
      
      <div class="row align-items-center">        
        <!-- header parte sopra -->
        <div class="col-12 contact">
          <div class="container">
            <div class="row justify-content-between">
            <div class="col-5">
              <div class="row">
                <div class="col-4">
                  <font-awesome-icon icon="fas fa-phone" />
                  <span>180009933489</span>
                </div>
                <div class="col-3 text-center">
                  <font-awesome-icon icon="fa-solid fa-envelope" />
                  <span>Contact Us</span></div>
                <div class="col-2 text-center">
                  <font-awesome-icon icon="fa-solid fa-graduation-cap" />
                  <span>Alunni</span>
                  </div>
                <div class="col-3 text-center">
                  <font-awesome-icon icon="fa-solid fa-building-columns" />
                  <span>Campus</span> 
                </div>
              </div>
            </div>
            <div class="col-2">
              <!-- icone social da mettere dopo con font awesome -->
              <div class="row">
                <div class="col-3 text-center">
                  <font-awesome-icon icon="fa-brands fa-facebook-f" />
                </div>
                <div class="col-3 text-center">
                 <font-awesome-icon icon="fa-brands fa-twitter" />
                </div>
                <div class="col-3 text-center">
                  <font-awesome-icon icon="fa-brands fa-youtube" />
                </div>
                <div class="col-3 text-center">
                  <font-awesome-icon icon="fa-brands fa-instagram" />
                </div>
              </div>
            </div>
          </div>
          </div>
          
        </div>
      </div>    

      <div class="row">
        <div class="col-12  header-height">
          <div class="container d-flex h-100">
            <div class="row justify-content-between align-self-center">
              <div class="col-3">
                <img src="../assets/university_logo.png" alt="">
              </div>
              <nav class=" col-9 align-self-center">
                <div class="row">
                  <ul class="col-12 d-flex">
                    <li v-for="(item,i) in linkHeader"
                    class="text-end ms-5"
                    :key="i">
                      <a href="item.link"><strong>{{item.select}}</strong></a>
                      <span>{{item.status}}</span>
                    </li>
                  </ul>
                </div>
                  
              </nav>
            </div>
          </div>          
        </div>
      </div>
        

      
    </div>
  </header>
</template>

<script>

export default {
  name: 'MyHeader',
  data() {
    return{
      linkHeader : [
        {
          select : 'HOME',
          link : '#'
        },
        {
          select : 'ABOUT',
          link : '#'
        },
        {
          select : 'COURSES',
          status : 'NEW',
          link : '#'
        },
        {
          select : 'EVENTS',
          link : '#'
        },
        {
          select : 'FACILITIES',
          link : '#'
        },
        {
          select : 'NEWS',
          link : '#'
        },
        {
          select : 'ADMISSION',
          status : 'APPLY',
          link : '#'
        },
      ],
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .contact {
    height: 50px; 
    background-color: #ffab0b;
    color: white;
    img{
      object-fit: contain;
      max-width: 60px;
      max-height: 60px;
      color: white;
    }
  }
  .header-height{
    height: 100px;
  }
  
</style>