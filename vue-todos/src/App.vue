<script setup>
import {RouterView} from "vue-router";
import ToDoHeader from "@/components/ToDoHeader.vue";


</script>

<template>
  <ToDoHeader/>

  <RouterView/>


</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto+Serif:ital,wght@1,100;1,400&family=Ubuntu+Mono&family=Ubuntu:ital@1&display=swap');

* {
  font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}

</style>
