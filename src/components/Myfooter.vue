<template>
  <footer id="img-footer" class="container-fluid">                     
    <myFooterList
    :linkFooter="linkFooter"
    :key="i"/>
  </footer>
</template>

<script>
import myFooterList from "./myFooterList";
export default {
  name: 'MyFooter',
  components : {
    myFooterList
  },
  data() {
    return{
      linkFooter : [
        {
          class : 'col-2',
          subtitle : 'AVADA UNIVERSITY',
          text : 'Residential Location 9521 Broadsberry Avenue Paddington RC7 9ZA', 
          icon : ''
        },
        {
          text : '1.800.458.556',
          icon : ''
        },
        {
          text : 'info@your-domain.com',
          icon : ''
        },
        {
          text : 'Monday – Friday: 8:00 AM – 10:00 PM',
          icon : ''
        },
        {
          class : 'col-2',
          subtitle : 'RECENT POSTS',
          text : 'What do successful grads think you should study?',
          icon : ''
        },
        { 
          text : 'Former student discusses success in the fashion industry',
          icon : ''
        },
        {          
          text : 'How do you best prepare for university?',
          icon : ''
        },
        {
          class : 'col-2',
          subtitle : 'Courses',
          text : 'Arts & Humanities'
        },
        {
          text : 'Buisness & Management'
        },
        {
          text : 'Engineering & Technology'
        },
        {
          text : 'Life Science & Medicine'
        },
        {
          text : 'Natural Scienses'
        },
        {
          subtitle: 'ADMISSION',
          text : 'Elegibility'
        },
        {
          text : 'Application'
        },
        {
          text : 'Review Process'
        },
        {
          text : 'How to Apply'
        },
        {
          class : 'col-2',
          subtitle: 'RESOURCES',
          text : 'Campus Directory'
        },
        {
          text : 'Academic Calendar'
        },
        {
          text : 'Sports Club'
        },
        {
          text : 'Graduate Programs'
        },
        {
          text : 'Faculty & Staff'
        },
        {

          subtitle: 'QUICKLINKS',
          text : 'University Library'
        },
        {
          text : 'Campus Service'
        },
        {
          text : 'Careers'
        },


      ]
    }
  },
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  #img-footer{
    background-image: url(../assets/university_ft_bg.png );
    
  
  }
</style>