<template>
  <div>
    <header>
        <div>
           <img class="lgo" src="~assets/pic.jpg" alt="">
       </div>
            <a href="#"><div class="rg">Home</div></a>
            <a href="#"><div class="rg">About</div></a>
             <a href="#"><div class="rg">Service</div></a>
           
       
    </header>
    <section class="section_1">
        <div></div>
        <div></div>
    </section>
    <section class="section_2">
       
            <div></div>
            <div></div>
        
    </section>
  </div>
</template>

<script>
export default {

}
</script>

<style  scoped>
header{
    background-color: bisque;
    height: 100px;
    border: 2px solid black;
}
.section_1{
    height: 60vh;
    border: 1px solid black;
    display: flex;
    flex: 0.3;
}
.section_1 div{
  height: 30vh;
  background-color: blue;
  flex: 0.3;
  margin: 1px;
}
.section_2{
    height: 60vh;
    display: flex;
    flex: 0.4;


}
.section_2 div{
     height: 30vh;
  background-color: rgb(84, 84, 153);
  flex: 0.3;
  margin: 1px;
}
.lgo{
    width: 10%;
  position: relative;
    margin-top: 20px;
    border-radius: 40px;
    height: 60px;
}
.rg{
    left: 900px;
    float: left;
    position: relative;
    margin: 40px;
}
</style>>


