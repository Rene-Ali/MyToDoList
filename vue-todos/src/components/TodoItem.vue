<template>
  <div>
    <h1> To do </h1>

  </div>
</template>

<script setup>
const props = defineProps({
  todo: {
    type: Object,
    required: true,
  },
});
</script>

<style lang="scss" scoped>

</style>