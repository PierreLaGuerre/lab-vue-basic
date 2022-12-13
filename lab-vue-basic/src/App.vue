<template>
   <Navbar />

  <section class="h-[300px] m-10">
    <h1 class="text-3xl my-5">Vue Basic</h1>
    <p class="my-5">Simple suma "2+2"= {{2+2}}</p>
    <p class="my-5">{{stringFunction()}}</p>
  </section>

  <Footer />

</template>

<script setup></script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
import {ref} from 'vue';
function stringFunction() {
  return("String example")
}
<style></style>