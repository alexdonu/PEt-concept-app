<script setup lang="ts"></script>
<template>
  <div class="filter">
    <div class="filter-box center">
      <div class="filter-box-title">Lorem Ipsum</div>
      <div class="filter-box-description">
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry.
      </div>
      <div class="filter-box-buttons">
        <button class="all-filters-button">
          <div class="all-filters-button-text center">All filters</div>
        </button>
        <button class="animal-species-button">
          <div class="animal-filters-button-text">Animal species</div>
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.filter {
  margin-top: 30px;
}
.filter-box {
  width: 287px;
  height: 131px;
}

.filter-box-title {
  color: #cd5b25;
  font-size: 18px;
  font-weight: 700;

  display: flex;
  justify-content: center;
  align-items: center;
}

.filter-box-description {
  color: #000;
  text-align: center;
  font-size: 13px;
  font-style: normal;
  font-weight: 300;
  line-height: normal;
  margin-top: 9px;

  display: flex;
  justify-content: center;
  align-items: center;
}

.filter-box-buttons {
  display: flex;
  justify-content: space-between;
  margin-top: 30px;
}

.all-filters-button {
  width: 124px;
  height: 29px;

  border: none;
  border-radius: 5.365px;
  background: #cd5b25;
}

.all-filters-button-text {
  display: flex;
  width: 70px;
  height: 23px;
  flex-direction: column;

  color: #d9d9d9;
  font-size: 15px;
  font-weight: 700;
}

.animal-species-button {
  display: flex;
  width: 124px;
  height: 23px;
  justify-content: center;
  align-items: center;

  border: none;
  background: #d9d9d9;
  color: #cd5b25;
  font-weight: 700;
}

.animal-filters-button-text{
  display: flex;  
}
</style>
