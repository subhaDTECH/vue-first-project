<template>
    <div class="continer">
         <div class="row">
               <div class="col-md-10 mx-auto  p-5">
                     <form  class="p-5">
                          <h3>{{username}}</h3>
                          <h3>Signup</h3>
                         <div class="form-group form__div">
                               <input v-model="signup.name" type="text " placeholder="Enter your name" class="from-control input__box">

                         </div>
                         <div class="form-group form__div">
                               <input v-model="signup.email" type="email " placeholder="Enter your Email" class="from-control input__box">

                         </div>
                         <div class="form-group form__div">
                               <input v-model="signup.password" type="password " placeholder="Enter your Password" class="from-control input__box">

                         </div>
                          <div class="form-group form__div">
                              <button type="submit" v-on:click="formsubmit" class="btn btn-info input__box" >
                                  submit
                              </button>

                         </div>

                     </form>

               </div>

         </div>

    </div>
</template>
<script>
export default {
    name:"Contact",
      methods:{
        formsubmit(e){
            e.preventDefault()
            console.log("hii")
            console.log(e.target[0])
            console.log(this.signup)
             console.log(this.signup.name)
             alert("welcome ,"+ this.signup.name)
             this.username=this.signup.name

             this.signup={
                 name:"",
                 email:"",
                 password:""
             }
            //  this.$routes.push('/')
        }
    },
    data(){
        return {
            signup:{
                name:"",
                email:"",
                password:""
            },
            username:"",
        }
    },
  
    
}
</script>

<style scoped>
 .continer{
     margin-top: 55px;
     width: 80vw;
     height: 84vh;
 }
 .form__div{
      margin:20px;
 }
 .input__box{
     padding: 10px 20px;
     width: 60%;
 }
</style>