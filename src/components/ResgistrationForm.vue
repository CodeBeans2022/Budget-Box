<template>
 <div class="container">
 
      <a href="/login" class="backlogin"><svg xmlns="http://www.w3.org/2000/svg" width="30" fill="currentColor" class="bi bi-arrow-90deg-left" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M1.146 4.854a.5.5 0 0 1 0-.708l4-4a.5.5 0 1 1 .708.708L2.707 4H12.5A2.5 2.5 0 0 1 15 6.5v8a.5.5 0 0 1-1 0v-8A1.5 1.5 0 0 0 12.5 5H2.707l3.147 3.146a.5.5 0 1 1-.708.708l-4-4z"/>
</svg></a>
    
  
  <div class="row">
    <div class="col">
      <h2>Sign up</h2>
    </div>
  </div>
  <div class="row">
    <div class="col">
     <form action="https://formspree.io/f/xdojdjnj" method="POST" target="_blank">
      <input type="text" placeholder="Username">
      <input type="email" placeholder="Email">
      <input type="password" placeholder="Password">
     <input type="password" placeholder="Confirm Password">
      <a href=""><button class="btn btn-success" type="submit">Create Account</button></a>
     </form>
    </div>
  </div>
 </div>
</template>

<script>
    export default {
        name: 'RegisterForm'
    }
</script>

<style scoped>
.backlogin{
  float: left;
  color: black;
  background-color: lightgreen;
  border-radius: 20px;
  padding: 10px;
}

.backlogin:hover{
  background-color:mediumseagreen;
}

form{
  display: flex;
  flex-direction: column;

}

input{
  margin-bottom: 20px;
  height: 50px;
  text-align: center;
  border: none;
  border-bottom: 1px solid black;
}


.container{
  margin-top: 70px;
}
</style>