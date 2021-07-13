<template>
  <div class="product-card">
    <img :src="thumb" />
    <h3>{{ title }}</h3>
    <h4>{{ price }}</h4>
    <h4>{{ type }}</h4>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    thumb: String,
    price: String,
    title: String,
    type: String,
  },
};
</script>

<style scoped lang="scss">
.product-card {
  color: white;
  padding: 0 15px;
  width: calc(100%/6) ;
  img{
    width: 150px;
    height: 150px;
  }
  
}
</style>
