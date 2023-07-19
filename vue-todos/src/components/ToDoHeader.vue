<template>
  <header>
    <nav class="container">
      <div class="branding">
        <img src="../assets/Vue_Logo_Black.png" alt="">
        <h1> Vue Todos</h1>
      </div>
      <ul class="nav-routes">
        <RouterLink to="/">Home</RouterLink>
        <Routerlink to="/about">About</Routerlink>
      </ul>
    </nav>
  </header>
</template>

<script setup>
import {Routerlink} from "vue-router";


</script>

<style lang="scss" scoped>

</style>