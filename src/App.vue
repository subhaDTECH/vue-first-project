<template>


<nav class="bg-dark main__nav ">
  <div class="title">
     <h3>VUEJS</h3>
  </div>
  <div class="menu ">
          <router-link class="nav_link" to='/'>Home</router-link> 
  <router-link class="nav_link" to='/about'>About</router-link>
  <router-link class="nav_link" to='/contact'>Conatct</router-link>
  <router-link class="nav_link" to='/service'>Service</router-link>
  <router-view></router-view>
  </div>
  
 

</nav>
 

 
  
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import About from './components/About.vue'
// import Home from './components/Home.vue'
// import Contact from './components/Contact.vue'
// import Service from './components/Service.vue'

export default {
  name: 'App',
  components: {
   
    
  }
}
</script>

<style >
*{

  margin: 0;
  padding: 0;
  box-sizing: border-box;
  }


.nav_link{
     margin-right: 20px;
     color: aliceblue;
     text-decoration: none;
     font-size: 16px;
     border: 1px solid white;
     padding: 10px 20px;
     margin-top: 10px;
  }
  .nav_link:hover{
    background-color: #fff;
    transition:0.5s  ;
  }
  nav{
           
           color: aliceblue;
           text-align: center;
          padding: 20px;
    }
    .main__nav{
      display: flex;
      justify-content: space-around;
      align-content: center;

    }

</style>
