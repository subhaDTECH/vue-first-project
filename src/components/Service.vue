<template>
    <div class="container service">
        <div class="row ">
              <div class="col-md-10 mt-4 p-4 main__serv">
                  <div class="col-md-6 col-12 mt-3 p-3">
                     <img class="img-fluid service__img" src="https://tse4.mm.bing.net/th?id=OIP.anXhrQvRtLngX2b9eIIC8gHaHa&pid=Api&P=0&w=300&h=300" alt="">
                  </div>
                  <div class="col-md-6 mt-5 p-2">
                     <h3>Our Services </h3>
                     <p>Web Design</p>
                     <p>Hosting</p>
                     <p>Domain</p>
                     <p>Free courses</p>
                  </div>
                    
              </div>

        </div>
    </div>
</template>
<script>
export default {
    name:"Service",
    
}
</script>

<style scoped>
 .service{
     margin-top: 52px;
     width: 80vw;
     height: 84vh;
  
 }
 .service__img{
     width: 300px;
     height: 300px;
 }
 .main__serv{
     display: flex;
     justify-content: space-between;
 }
</style>