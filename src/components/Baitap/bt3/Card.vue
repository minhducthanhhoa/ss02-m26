<template>
  <div class="card">
    <div class="image-placeholder">Image</div>
    <div class="title">Title</div>
    <button class="add-button">Add to cart</button>
  </div>
</template>

<style scoped>
.card {
  width: 200px;
  border: 1px solid #ccc;
  border-radius: 10px;
  overflow: hidden;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  margin: 10px;
}

.image-placeholder {
  background-color: #ccc;
  height: 120px;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 18px;
  color: white;
}

.title {
  padding: 10px;
  font-size: 16px;
  font-weight: bold;
  background-color: #f9f9f9;
}

.add-button {
  background-color: white;
  border: 1px solid #ccc;
  padding: 10px;
  width: 80%;
  margin: 10px auto;
  cursor: pointer;
}

.add-button:hover {
  background-color: #f0f0f0;
}
</style>
