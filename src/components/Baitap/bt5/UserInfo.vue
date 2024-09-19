<template>
  <div class="user-info">
    <h2>Thông tin cá nhân</h2>
    <p><strong>Họ và tên:</strong> {{ user.name }}</p>
    <p><strong>Tuổi:</strong> {{ user.age }}</p>
    <p><strong>Email:</strong> {{ user.email }}</p>
    <p><strong>Địa chỉ:</strong> {{ user.address }}</p>
  </div>
</template>

<script setup>
import { reactive } from 'vue';

const user = reactive({
  name: 'Nguyễn Văn A',
  age: 30,
  email: 'nguyenvana@example.com',
  address: '123 Đường ABC, TP. Hồ Chí Minh'
});
</script>

<style scoped>
.user-info {
  font-family: Arial, sans-serif;
  margin: 20px;
}

.user-info h2 {
  color: #2c3e50;
}

.user-info p {
  margin: 5px 0;
}
</style>
