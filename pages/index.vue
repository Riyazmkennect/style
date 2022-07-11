<template>
  <div>
    <header>
       <img class="logo" src="~assets/pic.jpg" alt="">
       <div class="li">
            <div class="link"><a href="/web">Home</a></div>
            <div class="link"><a href="/inspire">About</a></div>
            <div class="link"><a href="/Login">Login</a></div>
            <div class="link"><a href="https://www.google.com/">Contact us</a></div>
       </div>
    </header>
  
    <section>
      <aside></aside>
      <aside></aside>
     
      <main>
        <div></div>
        <div></div>
      </main>
    </section>
     <section class="block">
        <div class="b"></div>
        <div class="b"></div>
        <div class="b"></div>
         <div class="b"></div>
        <div class="b"></div>
        <div class="b"></div>
      </section>
      
      <div class="btm"></div>
    

  </div>
</template>
<script>
export default {
  components:{
  
}
}
</script>
<style>
.logo{
    width: 60px;
    height: 90px;
     flex-wrap: wrap;
    border-radius: 50%;
}

.link{
    left: 860px;
    float: left;
    position: relative;
    padding: 10px;
    padding-left: 40px;
    font-size: large;
    flex-wrap: wrap;
    
   
    margin-bottom: 100px;
    margin-top: -60px;
    
}
header{
  background-color: black;
  height: 100px;

  flex-wrap: wrap;
}
section{
  height: auto;
  display: flex;
  flex-wrap:wrap ; border: 2px solid black;

}
aside{
  background-color: rgb(121, 54, 184);
  flex: 0.6;
 
  height: 70vh;
  margin: 1px;
}

main{
  height: 70vh;
  flex: 0.6;
 
}
main div{
  background-color: rgb(46, 46, 85);
  height: 35vh;
  flex: 0.3;
  margin: 1px;
}
.btm{
  background-color: rgb(114, 62, 62);
  flex: 1;
  height: 100px;
  

}
.block{
  height: 40vh;
  display: flex;
  flex: 0.2;
  flex-wrap: wrap;
 
}
.block .b{
  margin: 1px;
  flex-wrap: wrap;
  flex: 0.2;
  height: 258px;
  background-color: rgb(65, 61, 61);
}


@media(max-width:800px){
  header{
    flex: 100%;
    max-width: 600px;
  }
   section{
    flex: 100%;
    max-width: 600px;
  }
   aside{
    flex: 100%;
    max-width: 600px;
  }
   main{
    flex: 100%;
    max-width: 600px;
  }
   main div{
    flex: 100%;
    max-width: 600px;
  }
   .block {
    flex: 100%;
    max-width: 600px;
  }
   .block .b{
    flex: 100%;
    max-width: 600px;
  }
  .btm{
    flex: 100%;
    max-width: 600px;
  }

}
</style>