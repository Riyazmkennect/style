<template>
  <div class="bg" >
    <div class="login">
        <h1>Welcome</h1>
        <p>Enter your credential to access account</p>
        <form action="message">
            <div class="email">
            
                <input type="text" placeholder="Email Id">
                    <i class="fa fa-envelope ic" aria-hidden="true"></i>
            </div>
            <div class="pass">
               
                <input type="password" placeholder="Password">
                 <i class="fa fa-unlock-alt" aria-hidden="true"></i>
            </div>
            <div class="btn">
                <input type="button" value="Login">
            </div>
            <div>
                <a href="#"> Create account</a>
            </div>
        </form>

    </div>

  </div>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
h1{
    padding: 30px;
    padding-left: 100px;
}
p{
    padding-left: 50px;
    margin-top: -20px;
    padding-bottom: 42px;
}
.login{
    top: 21%;
    left: 36%;
    position: absolute;
    width: 360px;
    height: 400px;
    background-color: rgb(120, 120, 161);
}
.login input {}
.login input{
    width: 96%;
    padding: 10px;
    margin: 12px;
  
}
.ic{
   margin-right: 16px;
}
.btn input{
     width: 96%;
    padding: 10px;
    margin: 12px;

    background-color: beige;
}
a{
    padding: 130px;
    padding-top: 40px;
}
.bg{
    background-color: rgb(128, 128, 175);
}
.email input [type=text]{
   padding-left: 40px;
}
.email{
    position: relative;
}
.email i{
    position: absolute;
   left: 14px;
    top: 20px;

}
.pass input [type=password]{
   padding-left: 40px;
}
.pass{
    position: relative;
}
.pass i{
    position: absolute;
   left: 14px;
    top: 20px;

}
</style>