<template>
  <div>
    <h2>Danh sách kết quả</h2>
    <ul>
      <li>{{ number1 }} + {{ number2 }} = {{ add() }}</li>
      <li>{{ number1 }} - {{ number2 }} = {{ subtract() }}</li>
      <li>{{ number1 }} * {{ number2 }} = {{ multiply() }}</li>
      <li>{{ number1 }} / {{ number2 }} = {{ divide() }}</li>
    </ul>
  </div>
</template>

<script setup>
import { ref } from 'vue';

const number1 = ref(10);
const number2 = ref(10);

const add = () => number1.value + number2.value;
const subtract = () => number1.value - number2.value;
const multiply = () => number1.value * number2.value;
const divide = () => number1.value / number2.value;
</script>

<style scoped>
h2 {
  font-size: 24px;
  font-weight: bold;
  text-align: center;
}

ul {
  list-style-type: disc;
  margin-left: 20px;
}

li {
  font-size: 18px;
  margin-bottom: 10px;
}
</style>
