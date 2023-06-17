<script setup>
import appLogo from "./assets/nuxt-logo.png";

const appName = "Grad Pro Tracker";
</script>
<template>
  <header class="app-header">
    <div class="app-info">
      <img :src="appLogo" alt="App logo" class="logo" />
      <h1 class="name">{{ appName }}</h1>
    </div>
  </header>
</template>
<style scoped>
.app-header {
  padding: 16px 32px;
  background-color: rgb(38, 127, 182);
}
.app-header > .app-info {
  display: flex;
  align-items: center;
  gap: 8px;
}
.app-header > .app-info > .name {
  color: #ffffff;
  margin: 0;
}
.app-header > .app-info > .logo {
  height: 48px;
  width: 48px;
}
</style>
