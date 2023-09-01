<template>
  <div class="wrapper">
    <header>
      <HeaderComp />
    </header>
    <aside>
      <AsideComp />
    </aside>
    <main>
      <MainComp />
    </main>
  </div>
</template>
<script setup>
  import HeaderComp from './components/HeaderComp.vue'
  import AsideComp from './components/AsideComp.vue'
  import MainComp from './components/MainComp.vue'
</script>


<style scoped>

.wrapper{
  height: 100vh;
  width: 100vw;
}
header {
  height: 8%;
}
aside {
  display: none;
  background-color: aqua;
  height: 100vh;
  position: absolute;
  top: 0;
  width: 100%;
  background: linear-gradient(90deg, rgba(143,143,203,1) 65%, rgba(73,73,80,0.5) 65%); 
}
main {
  height: 90%;
  width: 100vw;
  background-color: aqua;
}
 /* .wrapper {
  display: grid;
  grid-template-columns: 25% 1fr;
  grid-template-rows: 10% 1fr;
  height: inherit;
  width: inherit;
 }
 header {
  grid-column: 1/3;
  grid-row: 1/2;
  background-color: aqua;
  height: 100%;
  width: 100%;
 }
 aside {
  grid-column: 1/2;
  grid-row: 2/3;
  background-color: blueviolet;
 }
 main {
  grid-column: 2/3;
  grid-row: 2/3;
  background-color: yellow;
 } */
</style>
