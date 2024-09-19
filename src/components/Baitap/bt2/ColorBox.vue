<template>
  <div>
    <div class="color-box" :style="{ backgroundColor: color }">
      <span>Box</span>
    </div>
    <div class="color-label">{{ color }}</div>
  </div>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps({
  color: {
    type: String,
    required: true
  }
});
</script>

<style scoped>
.color-box {
  width: 200px;
  height: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 20px;
  color: white;
  margin-bottom: 10px;
}

.color-label {
  text-align: center;
  font-size: 16px;
  color: #333;
}
</style>
