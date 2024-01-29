<script setup>
const props = defineProps({
  productImageUrl: String,
  productTitle: String,
  productOwnerName: String,
  productPrice: String,
});
</script>

<template>
  <div class="product-card-container card pt-4 pb-4 shadow">
    <img :src="productImageUrl" class="card-img-top" alt="Product img" />
    
    <div class="card-body">
      <h3>
        {{ productTitle }}
      </h3>
      <h4 class="text-center">
        por <span class="fst-italic" > {{ productOwnerName }} </span>
      </h4>
      <span class="d-block text-center fw-bolder fs-3">
        $ {{ productPrice }}
      </span>
    </div>
    
    <button
      type="submit"
      class="rounded-md self-center bg-blue-400 font-bold px-6 py-2 text-sm text-white shadow-sm hover:bg-blue-500 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600"
    >
      Comprar ahora
    </button>
  </div>
</template>

<style scoped>
  h3{
  width: 400px;
  font-family: "Inter", sans-serif;
  text-align: center;
  font-size: 30px;
  color: black;
  vertical-align: baseline;
  letter-spacing: -1.5px;
  word-spacing: 0px;
  }

  img{
    width: 180px;
    height: 150px;
    align-self: center;
  }

  .product-card-container{
    width: 420px;
    height: 400px;
  }
</style>
