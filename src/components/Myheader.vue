<template>
  <header>
    <div class="container-fluid">
      
      <div class="row">        
        <!-- header parte sopra -->
        <div class="col-12 contact">
          <div class="container">
            <div class="row justify-content-between">
            <div class="col-5">
              <div class="row">
                <div class="col-3">
                  <span>180009933489</span>
                </div>
                <div class="col-3 text-center">Contact Us</div>
                <div class="col-3 text-center">Alunni</div>
                <div class="col-3 text-center">Campus</div>
              </div>
            </div>
            <div class="col-2">
              <!-- icone social da mettere dopo con font awesome -->
              <div class="row">
                <div class="col-3 text-center">fb</div>
                <div class="col-3 text-center">insta</div>
                <div class="col-3 text-center">twitter</div>
                <div class="col-3 text-center">pinterest</div>
              </div>
            </div>
          </div>
          </div>
          
        </div>
        
        <div class="col-12 header-height ">
          <div class="container">
            <div class="row">
              <div class="col-3">
                <img src="../assets/university_logo.png" alt="">
              </div>
              <nav class="col-9 align-self-center">
                <ul class="row justify-content-between">
                  <li v-for="(item,i) in linkHeader"
                  class="col-1 text-center"
                  :key="i">
                    <a href="item.link"><strong>{{item.select}}</strong></a>
                  </li>
                </ul>
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
      ]
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .contact {
    height: 50px; 
    background-color: #ffab0b;
  }
  .header-height{
    height: 150px;
    nav ul li {
    list-style: none;
      a{
        text-decoration: none;
        color: black;
      }
    }
  }
  
</style>