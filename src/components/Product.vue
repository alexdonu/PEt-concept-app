<script setup lang="ts">
import InfoIcon from '../icons/InfoIcon.vue'
import HeartIcon from '../icons/HeartIcon.vue'
</script>

<template>
  <div class="center">
    <div class="product-image">
      <img src="../files/product.jpeg" class="image" alt="product image" />
      <div class="controls">
        <div class="info">
          <InfoIcon />
        </div>
        <div class="like">
          <HeartIcon />
        </div>
      </div>
    </div>
    <div class="text">
      <div class="title-price">
        <div class="product-title">Lorem Ipsum</div>
        <div class="product-price">$ 00</div>
      </div>
      <div class="product-description">
        Lorem Ipsum is simply dummy text of the printing
      </div>
    </div>
  </div>
</template>

<style>
.image {
  width: 124px;
  height: 118px;
  border-radius: 4px;
}

.product-image {
  position: relative;
}

.text {
  width: 124px;
}

.title-price {
  display: flex;
  justify-content: space-between;
  margin-top: 22px;
}

.product-title {
  color: #000;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: -0.825px;
}

.product-price {
  color: #cd5b25;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: -0.825px;
}

.product-description {
  margin-top: 8px;
  width: 129px;
  height: 42px;
  flex-direction: column;
  justify-content: center;
  flex-shrink: 0;

  color: #000;
  font-size: 13px;
  font-weight: 300;
  letter-spacing: 0.13px;
}

.controls {
  position: absolute;
  width: 18px;
  height: 40px;
  top: 0px;
  right: 1px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  background: #D9D9D9;
  border-radius: 0px 4px 0px 4px;
}

.info{
  width: 11px;
  height: 11px;
  display: flex;
}

.like {
  width: 11px;
  height: 11px;
  display: flex;
}
</style>
