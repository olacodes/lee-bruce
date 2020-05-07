<template>
  <div class="price-listing-container">
      <h2>Lee-Bruce Price Listing</h2>
      <div class="price-list">
          <PriceList v-bind:datas="datas" />
      </div>
  </div>
</template>

<script>
import PriceList from './PriceList'

export default {
    components: {
        PriceList
    },
    data: function() {
    return {
      datas: [
            {
            plan: "Bronze",
            price: "$26",
            time: "per month",
            offer: [
              "lorem ipsum content",
              "lorem ipsum content",
              "lorem ipsum content",
            ],
          },
            {
            plan: "Silver",
            price: "$40",
            time: "per month",
            offer: [
              "lorem ipsum content",
              "lorem ipsum content",
              "lorem ipsum content",
            ],
          },
            {
            plan: "Gold",
            price: "$100",
            time: "per month",
            offer: [
              "lorem ipsum content",
              "lorem ipsum content",
              "lorem ipsum content",
              "lorem ipsum content",
            ],
          },
      ],
    };
  },
}
</script>

<style>

</style>