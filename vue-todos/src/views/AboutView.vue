<template>
  <div class="about">
    <div class="to-do">
      <h2>To-do Application</h2>
      <div class="icon-and-text">
        <Icon icon="bx:copyright" width="22" margin-top="10"/>
        <p>Ein Projekt von René-Ali Günürün</p>
      </div>
      <small class="italic">Diese Webseite dient ausschließlich als technisches Showcase und keinen
        kommerziellen Zwecken.</small>
      <small>Wien, 2023</small>
    </div>
  </div>
</template>

<script setup>
import {Icon} from '@iconify/vue';
</script>

<style>
.about {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  width: 100%;
  margin: 0 auto;
  padding: 40px 16px;
}

.icon-and-text {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
  margin-bottom: 0.5rem;
}

h2 {
  color: blue;
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

p {
  margin-top: 0.5rem;
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

small {
  display: block;
  font-size: 0.8rem;
  color: gray;
  margin-bottom: 0.5rem;
}


.to-do {
  gap: 1rem;
  padding-bottom: 2.5rem;
  text-align: center;
}

</style>