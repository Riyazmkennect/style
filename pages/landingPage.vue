<template>
  <div>
    <header></header>
   <section>
    <aside></aside>
    <main>
        <div></div>
        <div></div>
    </main>
    </section>
    <div></div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
header{
    background-color: black;
    height: 100px;
}
section{
    height: auto;
    display: flex;
    flex-wrap: wrap;
    margin: 1px;
}
aside{
    background-color: blue;
    flex: 0.4;
    height: 80vh;
    margin: 1px;

}
main{
    height: 80vh;
    flex: 0.6;
}
main div{
    height: 40vh;
    margin: 1px;
    background-color: rgb(129, 82, 173);
}
div{
    background-color: gray;
    flex: 1;
    height: 100px;
}
</style>