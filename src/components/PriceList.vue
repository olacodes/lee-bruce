<template>
  <div class="price-list-container">
    <div v-for="data in datas" :key="data.name">
      <PriceCard v-bind:data="data" />
    </div>
  </div>
</template>

<script>
import PriceCard from "./PriceCard";

export default {

  components: {
    PriceCard
  },
  props:{
      datas:{
          type: Array
      }
  }
  
};
</script>

<style scoped>
    .price-list-container{
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
    }
</style>
