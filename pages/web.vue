<template>
  <div>
    <header>
        <img class="logo" src="~assets/pic.jpg" alt="">
       <div class="li">
            <div class="link"><a href="https://www.google.com/">Home</a></div>
            <div class="link"><a href="/inspire">About</a></div>
            <div class="link"><a href="/Login">Login</a></div>
            <div class="link"><a href="https://www.google.com/">Contact us</a></div>
       </div>
    </header>
    <section>
        <aside></aside>
        <main>
            <div class="sec"></div>
            <div class="sec"></div>
        </main>
    </section>
    
  </div>
</template>

<script>
export default {

}
</script>

<style>
.logo{
    width: 60px;
    height: 90px;
  
    border-radius: 50%;
}
header{
    border: 2px solid black;
    height: 100px;
}
.link{
    left: 860px;
    float: left;
    position: relative;
    padding: 10px;
    padding-left: 40px;
    font-size: large;
    
   
    margin-bottom: 100px;
    margin-top: -60px;
    
}
section{
    height: 100vh;
    flex: 1;
    margin: 1px;
  
}
aside{
    background-color: rgb(82, 82, 165);
    height: 60vh;
    margin: 1px;
    flex: 0.4;
}
main{
    background-color: rgb(152, 107, 194);
    flex: 0.6;
    margin: 1px;
    height:60vh ;
}
main  .sec{
    background-color: rgb(155, 114, 53);
    flex: 0.6;
    height: 30vh;
}
.btm{
    background-color: gray;
    height: 100px;
    margin: 2px;
}
</style>