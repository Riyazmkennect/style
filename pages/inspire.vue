<template>
 <div>
  <header></header>
  <section>
    <aside></aside>
    

   <div class="co2"></div>
    <div class="co3"></div>
   <div class="co4"></div>
  
  
  
  </section>
  <div class="a"></div>
  <div class="w"></div>
 </div>
</template>

<script>
export default {
  name: 'InspirePage'
}
</script>
<style>
header{
  background-color: black;
  flex-wrap: wrap;
  height: 100px;

}
section{
  border: 2px solid black;
  display: flex;
  flex-wrap: wrap;
  height:auto;
}
aside{
  background-color: rgb(157, 157, 182);
  flex: 0.6;
  flex-wrap: wrap;
  margin: 2px;
  height: 65vh;
}


.co2{
  background-color: rgb(130, 130, 185);
  flex: 0.3;
  flex-wrap: wrap;
  height: 65vh;
  margin: 2px;

}
.co3{
  background-color: rgb(224, 224, 243);
  flex: 0.3;
  flex-wrap: wrap;
  height: 65vh;
  margin: 2px;

}

.co4{
  background-color: rgb(2, 2, 250);
  flex: 0.6;
  flex-wrap: wrap;
  height: 65vh;
  margin: 2px;

}
.a{
  background-color: rgb(109, 64, 151);
  flex-wrap: wrap;
  height: 100px;
  flex: 1;

}
.w{
  background-color: rgb(156, 156, 154);
  flex-wrap: wrap;
   height: 100px;
  flex: 1;

}
@media (max-width:800px){
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
  .co2{
    flex: 100%;
    max-width: 600px;
  }
  .co3{
    flex: 100%;
    max-width: 600px;
  }
  .co4{
    flex: 100%;
    max-width: 600px;
  }
  .a{
    flex: 100%;
    max-width: 600px;
  }
 .w{
    flex: 100%;
    max-width: 600px;
  }
}
</style>