<template>
    <section class="container-fluid py-5 background-grey border-radius align-items-center">
        <div class="container">
            <div class="row justify-content-between">             
                    <div class="col-6">
                        <h2>WORLD CLASS FACILITIES</h2>
                        <p class="my-4 fs-5 text-secondary">Avada University is devoted to excellence in teaching, learning, and research, and developing leaders in many disciplines who make a difference globally.</p>
                        <ul>
                            <li>
                                <strong class="fs-5">
                                    <font-awesome-icon class="icon-color" icon="fa-solid fa-globe" /> International focus
                                </strong>
                                <span class="text-secondary fs-5"> – our students come from across the globe</span>
                            
                            </li>
                            <li>
                                <strong class="fs-5">
                                    <font-awesome-icon class="icon-color" icon="fa-solid fa-graduation-cap" /> Residential courses
                                </strong>
                                <span class="text-secondary fs-5"> – we encourage learning and growth</span>                            
                            </li>
                            <li>
                                <strong class="fs-5">
                                    <font-awesome-icon class="icon-color" icon="fa-solid fa-address-book" /> People not profits
                                </strong>
                                <span class="text-secondary fs-5"> – education is a right not a privilege</span>
                            </li>
                        </ul>
                        <p class="mt-4 fs-5 text-secondary">If you prefer to study in your own time and at your own speed then one of our e-learning packages may be right up your street.</p>
                    </div>
                    <div class="col-6">                        
                        <ul>
                            <li>
                                <h2>OUR VALUES</h2>
                            </li>
                            <li class="our-list">
                                <a href="#"> + OUR MISSION</a>                          
                            </li>
                            <li class="our-list">
                                <a href="#"> + OUR PHILOSOPHY</a>                          
                            </li>
                            <li class="our-list">
                                <a href="#"> + OUR OUR COMMITENT</a>                          
                            </li>
                            <li class="our-list">
                                <a href="#"> + OUR PROMISE</a>                          
                            </li>
                            <li class="our-list">
                                <a href="#"> + OUR VALUES</a>                          
                            </li>
                        </ul>
                    </div>                  
            </div>
        </div>            
                
    </section>
</template>

<script>
export default {
  name: 'WhyStart'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    .icon-color{
            color: #ef993e;
    }
    li{
        list-style: none;
    }
    .our-list{
        
        background-color: white;
        margin-bottom: 10px;
        padding: 10px;
        
        a{
            text-decoration: none;
            color: orange;
            font-size: 24px;
        }
    }
</style>