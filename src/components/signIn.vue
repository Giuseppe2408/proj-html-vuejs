<template>
  <section id="signIn" class="container-fluid">
    <div class="container py-5">
        <div class="row justify-content-center">
            <div class="col-12 text-center">
                <h2>Joing Over <span id="students">500,000 Students</span>  Enjoying Avada Education now</h2>
            </div>
            <div class="mb-4 col-12 text-center">
                <span>Become Part of Avada University to Further Your Career.</span>
            </div>
            <div class="col-12">
                <div class="row justify-content-center">
                    <div class="col-3">
                        <input type="text" placeholder="Name">
                    </div>
                    <div class="col-3">
                        <input type="email" placeholder="Email">
                    </div>
                    <div class="col-3">
                        <input type="text" placeholder="Phone">
                    </div>
                    <div class="col-3">
                        <button id="orange-btton">APPLY NOW</button>
                    </div>
                </div>
            </div>
            
        </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'HelloWorld'
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    #signIn{
        background-color: #333c4e;
        color: white;
        #orange-btton{
            width: 100%;
            padding: 11px;
            background-color: #ffab0b;
            border: #ffab0b;
            color: white;
        }
        #students{
            color: orange;
            border-bottom: 1px solid orange;
            border-radius: 50%;
            transform: rotate(50%);
        }
        input{
            width: 100%;
            color: white;
            padding: 10px;
            background-color: #47536c;
            border-color: transparent;
        }
    }
</style>