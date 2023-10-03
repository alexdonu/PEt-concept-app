<script setup lang="ts">
import Header from "./components/Header.vue";
import Filter from "./components/Filter.vue";
import Product from "./components/Product.vue";
import MoreProductsButton from "./components/MoreProductsButton.vue";
import Footer from "./components/Footer.vue";
</script>

<template>
  <Header />
  <Filter />

  <div class="products-container">
    <div class="product center">
      <Product v-for="product in 12" :key="product" />
    </div>
  </div>

  <MoreProductsButton />
  <Footer />
</template>

<style scoped>
.products-container {
  margin-top: 30px;
}

.product {
  width: 287px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  grid-gap: 32px;
}
</style>
