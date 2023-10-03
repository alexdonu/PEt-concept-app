<script setup lang="ts"></script>

<template>
  <header class="header">
    <div class="header-box center">
      <div class="logo">LOGO</div>
      <div class="menu">
        <div>
          <div class="line" />
          <div class="line" />
          <div class="line" />
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
.header {
  margin-top: 22px;
}

.header-box {
  display: flex;
  justify-content: space-between;
  height: 26px;
  width: 269px;
}
.menu {
  display: flex;
  align-items: center;
}

.line {
  background-color: black;
  margin-top: 2px;
  width: 18px;
  height: 2px;
}
.logo {
  font-weight: 700;
  font-size: 20px;
  line-height: 26px;

  width: 81px;
  height: 26px;
}
</style>
