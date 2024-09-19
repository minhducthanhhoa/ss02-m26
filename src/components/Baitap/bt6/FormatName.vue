<template>
  <div class="format-name">
    <h2>Họ và Tên:</h2>
    <p>{{ formatName(user) }}</p>
  </div>
</template>

<script setup>
    const user = {
        firstName: 'Nguyễn Văn',
        lastName: 'Nam'
    };

    function formatName(user) {
        return `${user.firstName} ${user.lastName}`;
    }
</script>

<style scoped>
.format-name {
  font-family: Arial, sans-serif;
  margin: 20px;
}

.format-name h2 {
  color: #2c3e50;
}

.format-name p {
  font-size: 18px;
}
</style>
