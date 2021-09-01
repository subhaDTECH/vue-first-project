<template>
    <div class="home__container">
          <div class="container mt-4">
               <div class="row  mt-5  ">
                     <div class="col-md-6 col-12 mt-5 p-5 content__part  text-info ">
                           <h3 class="mt-5 pt-4 main__text">Welcome to The Tech Hub</h3>
                             <h5>Explore the new ideas to the world</h5>
                             <p>Start join with us</p>
                             <button class="btn btn-info">Join Us</button>

                     </div>
                     <div class="col-md-6 col-12 mt-5 p-4">
                           <img class="img-fluid main__img" src="https://cdn.pixabay.com/photo/2013/07/13/01/11/beetle-155267_960_720.png" alt="">

                     </div>

               </div>

          </div>

    </div>
</template>
<script>
export default {
    name:"Home",
    
}
</script>


<style scoped>
.home__container{
    width: 80vw;
    height: 85vh;
}
 .main__img{
     width: 400px;
     height: 400px;
 }
 .content__part{
     margin-top: 20px;
     padding: 20px;
 }
 .main__text{
     font-size: 40px;
     font-weight: bold;
 }
</style>