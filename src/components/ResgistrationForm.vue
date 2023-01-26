<template>
 <div class="container">
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