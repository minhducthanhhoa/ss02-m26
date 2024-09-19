<template>
  <div class="main">
    <Cart v-for="n in 12" :key="n" />
  </div>
</template>

<script setup>
import Cart from './Cart.vue';
</script>

<style scoped>
.main {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  padding: 20px;
  background-color: #fff0f0;
  flex: 1;
  justify-content: center;
}
</style>
