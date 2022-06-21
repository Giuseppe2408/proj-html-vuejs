<template>
  <footer id="img-footer" class="container-fluid">
    <ul class="row">
      <li v-for="(link, i) in linkFooter"
      :key="i"
      :class="link.subtitle !== '' ? 'col-3' : ''">
        <h2>{{link.subtitle}}</h2>
        <a href="">{{link.contact}}</a>
      </li>
    </ul> 
  </footer>
</template>

<script>
export default {
  name: 'MyFooter',
  data() {
    return{
      linkFooter : [
        {
          subtitle : 'AVADA UNIVERSITY',
          contact : 'Residential Location 9521 Broadsberry Avenue Paddington RC7 9ZA',
          icon : ''
        },
        {
          contact : '1.800.458.556',
          icon : ''
        },
        {
          contact : 'info@your-domain.com',
          icon : ''
        },
        {
          contact : 'Monday – Friday: 8:00 AM – 10:00 PM',
          icon : ''
        },
        {
          subtitle : 'RECENT POSTS',
          contact : 'What do successful grads think you should study?',
          icon : ''
        },
        { 
          contact : 'Former student discusses success in the fashion industry',
          icon : ''
        },
        {          
          contact : 'How do you best prepare for university?',
          icon : ''
        },
        {
          subtitle : 'Courses',
          contact : 'Arts & Humanities'
        },
        {
          contact : 'Buisness & Management'
        },
        {
          contact : 'Engineering & Technology'
        },
        {
          contact : 'Life Science & Medicine'
        },
        {
          contact : 'Natural Scienses'
        },
        {
          subtitle: 'ADMISSION',
          contact : 'Elegibility'
        },
        {
          contact : 'Application'
        },
        {
          contact : 'Review Process'
        },
        {
          contact : 'How to Apply'
        },
        {
          subtitle: 'RESOURCES',
          contact : 'Campus Directory'
        },
        {
          contact : 'Academic Calendar'
        },
        {
          contact : 'Sports Club'
        },
        {
          contact : 'Graduate Programs'
        },
        {
          contact : 'Faculty & Staff'
        },
        {

          subtitle: 'QUICKLINKS',
          contact : 'University Library'
        },
        {
          contact : 'Campus Service'
        },
        {
          contact : 'Careers'
        },


      ]
    }
  }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  #img-footer{
    background-image: url(../assets/university_ft_bg.png );
  }
</style>