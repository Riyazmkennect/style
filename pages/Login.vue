<template>
  <div class="login">
     <div class="pa">
        <img class="pi" src="~assets/pic.jpg" alt="">
    </div>
    <h1>Login</h1>
   
    <form action="message">
        <div class="username">
            <p>username</p>
            <input type="text" placeholder="Enter Your Name">
        </div>
        <div class="password">
            <p>password</p>
            <input type="password" placeholder="Enter your password">
        </div>
        <div class="btn">
           <input type="button" value="Login">
        </div>
        <div class="op">
            <a href="#">New user?create account</a>
        </div>
    </form>

  </div>
</template>

<script>
export default {

}
</script>

<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
.login{
    top: 21%;
    left: 38%;
    position: absolute;
    width: 360px;
    height: 400px;
    background-color: bisque;
    box-shadow: rgba(rgb(92, 137, 221), rgb(97, 223, 97), rgb(114, 114, 182), alpha);
}
p{
   margin: 6px;
}
h1{
    margin-bottom: 24px;
    margin: 10px;
}
.login input{
    width: 96%;
    padding: 6px;
    margin: 10px;
}
.btn input{
    margin-top: 40px;
    width: 96%;
    background-color: azure;
    
    padding: 6px;
    margin-bottom: 30px;
    
}
.btn :hover{
    cursor: pointer;
    background-color: blue;
}
.op a{
    padding: 100px;
  
}

.pi{
    width: 40%;
    height: 60px;
    border-radius: 50%;
   
    position: relative;
    top: -40px;
    left: calc(50% - 50%);
   
   
}

</style>