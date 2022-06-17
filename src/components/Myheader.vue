<template>
  <header>
    <div class="container fluid">
      <div class="row">
        <div class="contact">
          <div class="col-12 bg-primary"></div>
        </div>
        
      </div>
    </div>
  </header>
</template>

<script>

export default {
  name: 'Myheader',
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
  }
</style>