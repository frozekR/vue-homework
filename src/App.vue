<script setup>
  let currentDate = new Date();
</script>

<template>
  <div> {{ currentDate.toDateString() }} </div>
</template>

<style scoped></style>
