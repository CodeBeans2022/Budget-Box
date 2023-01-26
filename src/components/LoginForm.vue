<template>
 <div class="container">
  <div class="row">
    <div class="col">
     <form action="POST">
      <input type="text" placeholder="Username">
      <input type="email" placeholder="Email">
      <input type="password" placeholder="Password">
      <a href="/register">Create Account</a>
      <a class="btn btn-success" href="/home">Submit</a>
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
  margin-bottom: 30px;
}
</style>
