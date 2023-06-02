<script setup>
const { cars } = useCars();
</script>
<template>
  <div class="w-full">
    <!-- CAR CARD START-->
    <CarCard v-for="car in cars" :key="car.id" :car="car" />
    <!-- CAR CARD END-->
  </div>
</template>
