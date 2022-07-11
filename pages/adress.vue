<template>
  <div>
    <header>
        <img class="logo" src="~assets/pic.jpg" alt="">
        <div>
            <div class="hed"><a href="#">Home</a></div>
            <div class="hed"><a href="#">About</a></div>
            <div class="hed"><a href="#">Login</a></div>
            <div class="hed"><a href="#">Service</a></div>
        </div>
    </header>
    <section>
        <aside></aside>
        <main>

        </main>
    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style>
header{
    background-color: aliceblue;
    height: 100px;
    flex-wrap: wrap;
    border: 2px solid black;
    
}
.logo{
    padding: 12px;
    width: 10%;
    flex-wrap: wrap;
    height: 100px;
    border-radius: 50px;

}
.hed{
    top: -60px;
    float: left;
    font-size: 20px;
    text-decoration: none;
    left: 960px;
    flex-wrap: wrap;
    padding-right: 40px;
    position: relative;
}
section{
    height: 100vh;
    display: flex;
    flex-wrap: wrap;
}
aside{
    background-color: rgb(127, 127, 184);
    flex: 0.6;
    height: 60vh;
}
@media (max-width:800px){
    header{
        flex: 100%;
        max-width: 600px;
    }
      .logo{
        flex: 100%;
        max-width: 600px;
    }
      .hed{
        flex: 100%;
        max-width: 600px;
    }
}
</style>