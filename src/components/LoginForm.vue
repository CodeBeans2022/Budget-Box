<template>
 <div class="container">
  <div class="row">
    <div class="col">
     <form action="https://formspree.io/f/xdojdjnj" method="POST" target="_blank">
      <input name="text" type="text" placeholder="Username">
      <input name="email" type="email" placeholder="Email">
      <input name="password" type="password" placeholder="Password">
      <a href="/register" class="create">Create Account</a>
      <a class="btn btn-success login mx-auto" href="/home">Login</a>
     </form>
    </div>
  </div>
 </div>
</template>

<script>
export default {
  name: 'LoginForm',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.create{
  color: black;

}
.create:hover{
  background-color: lightgreen;
  border-radius: 30px;

}
form{
  display: flex;
  flex-direction: column;
  margin: 100px;
}

input{
  margin-bottom: 20px;
  height: 50px;
  text-align: center;
  border: none;
  border-bottom: 1px solid black;
}
button{
  text-decoration: underline;
}

a{
  margin-bottom: 15px;
}

.login{
  height: 40px;
  width: 90px;
  margin: 10px;
}
</style>
