<script setup>
import HelloWorld from './components/HelloWorld.vue';
import Header from './components/Header.vue';
import Content from './components/Content.vue';
import Footer from './components/Footer.vue';
</script>

<template>
  <div class="flex flex-col text-center text-white bg-gray-900 custom-class">
    <Header/>
    <Content/>
    <!-- <HelloWorld msg="Vite + Vue" /> -->
    <Footer/>
  </div>
</template>

<style>

html,
body,
#app,
.custom-class  {
  height: 100%;
}

</style>
