<template>
 <div class="container">
  <div class="row">
    <div class="col">
        <h2>Sign up</h2>
     <form action="POST">
      <input type="text" placeholder="Username">
      <input type="email" placeholder="Email">
      <input type="password" placeholder="Password">
     <input type="password" placeholder="Confirm Password">
      <a href=""><button class="btn">Submit</button></a>
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
</style>