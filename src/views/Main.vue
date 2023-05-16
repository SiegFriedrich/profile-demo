<template>
  <div class="common-layout">
    <el-container>
      <el-header class="header">Header</el-header>
      <el-main class="main"><router-view></router-view></el-main>
    </el-container>
  </div>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped>
.header {
  position: inherit;
  height: 80px;
  background-color: burlywood;
  color: white;
  display: flex;
  justify-content: space-between;
}

.side {
  background-color: orange;
  height: 100vh;
}

.main {
  background-color: yellow;
  height: 100vh;
}
</style>
