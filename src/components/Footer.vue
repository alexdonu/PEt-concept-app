<script setup lang="ts"></script>

<template>
  <footer class="footer">
    <div class="footer-box center">
      <div class="logo">LOGO</div>
      <div class="menu">
        <div class="menu-logo">
          <div class="line" />
          <div class="line" />
          <div class="line" />
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  display: flex;
  align-items: center;
  margin-top: 68px;
  background: #CD5B25;
  height: 42px;
}

.footer-box {
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
