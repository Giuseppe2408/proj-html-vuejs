<template>
  <footer class="py-5 container-fluid">                     
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
          subtitle : 'AVADA UNIVERSITY',
          contact : 'Residential Location 9521 Broadsberry Avenue Paddington RC7 9ZA', 
          icon : '<font-awesome-icon icon="fa-solid fa-house"/>'
        },
        {
          contact : '1.800.458.556',
          icon : '<font-awesome-icon icon="fas fa-phone"/>'
        },
        {
          contact : 'info@your-domain.com',
          icon : '<font-awesome-icon icon="fa-solid fa-envelope"/>'
        },
        {
          contact : 'Monday – Friday: 8:00 AM – 10:00 PM',
          icon : '<font-awesome-icon icon="fa-solid fa-clock"/>'
        },
        {
          domandsubtitle : 'RECENT POSTS',
          domand : 'What do successful grads think you should study?',
          date : 'March 12/03/2019',
          icon : ''
        },
        { 
          domand : 'Former student discusses success in the fashion industry',
          date : 'August 17/08/2019',
          icon : ''
        },
        {          
          domand : 'How do you best prepare for university?',
          date : 'May 25/05/2020',
          icon : ''
        },
        {
          linkTitle : 'Courses',
          link1 : 'Arts & Humanities'
        },
        {
          link1 : 'Buisness & Management'
        },
        {
          link1 : 'Engineering & Technology'
        },
        {
          link1 : 'Life Science & Medicine'
        },
        {
          link1 : 'Natural Scienses'
        },
        {
          linkTitle: 'ADMISSION',
          link1 : 'Elegibility'
        },
        {
          link1 : 'Application'
        },
        {
          link1 : 'Review Process'
        },
        {
          link1 : 'How to Apply'
        },
        {
          linkTitle1: 'RESOURCES',
          link2 : 'Campus Directory'
        },
        {
          link2 : 'Academic Calendar'
        },
        {
          link2 : 'Sports Club'
        },
        {
          link2 : 'Graduate Programs'
        },
        {
          link2 : 'Faculty & Staff'
        },
        {

          linkTitle1: 'QUICKLINKS',
          link2 : 'University Library'
        },
        {
          link2 : 'Campus Service'
        },
        {
          link2 : 'Careers'
        },
        {
          calendario : 'calendario',
          eventsTitle : 'Upcoming Events',
          text : 'Buisness Seminair',
          dataevent : 'July-1 2019',
          location : 'united states',
          num : '27'
        },
        {
          calendario : 'calendario',
          text : 'Politics Seminair',
          dataevent : 'November-6 2019',
          location : 'united Kingdom',
          num : '27'
        },

      ]
    }
  },
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  footer{
    background-image: url(../assets/university_ft_bg.png );
    line-height: 40px;
  }
</style>