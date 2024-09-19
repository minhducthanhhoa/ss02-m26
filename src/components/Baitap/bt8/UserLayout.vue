<template>
  <div class="user-layout">
    <Header />
    <Navbar />
    <div class="content-area">
      <Menu />
      <Main />
      <Article />
    </div>
  </div>
</template>

<script setup>
import Header from './Header.vue';
import Navbar from './Navbar.vue';
import Menu from './Menu.vue';
import Main from './Main.vue';
import Article from './Article.vue';
</script>

<style scoped>
.user-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.content-area {
  display: flex;
  flex: 1;
}

header {
  background-color: #d3d3d3;
  text-align: center;
  padding: 20px;
}
</style>
