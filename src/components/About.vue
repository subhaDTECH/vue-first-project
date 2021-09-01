<template>
     <div class="home__container">
          <div class="container mt-4">
               <div class="row  mt-5  ">
                   <div class="col-md-6 col-12 mt-5 p-4">
                           <img class="img-fluid main__img" src="https://tse4.mm.bing.net/th?id=OIP.e6CkRBi87jX1nlL7QH8RlAHaHa&pid=Api&P=0&w=300&h=300" alt="">

                     </div>
                     <div class="col-md-6 col-12 mt-5 p-5 content__part  text-info ">
                           <h3 class="mt-5 pt-4 main__text">About Us</h3>
                             <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.
                                  Voluptatum fugit ipsum iure mollitia hic 
                                 rem dolores sit maxime deleniti sequi.</p>
                           <span> <p>Excllent speed</p> <p>Optimise Design</p>  <p>Ralibility</p></span>
                            
                            
                            
                      

                     </div>
                     

               </div>

          </div>

    </div>
</template>
<script>
export default {
    name:"About",
    
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
     border-radius: 40px;
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