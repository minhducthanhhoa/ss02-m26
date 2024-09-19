<template>
  <div class="admin-layout">
    <Header />
    <div class="content-area">
      <Menu />
      <Main />
    </div>
    <Footer />
  </div>
</template>

<script setup>
import Header from './Header.vue'
import Menu from './Menu.vue'
import Main from './Main.vue'
import Footer from './Footer.vue'


</script>

<style scoped>
.admin-layout {
  display: flex;
  flex-direction: column;
  height: 100vh;
}

.content-area {
  display: flex;
  flex: 1;
  background-color: #f0f0f0;
}
</style>
