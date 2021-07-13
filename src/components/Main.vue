<template>
  <div class="main-section">
    <div class="container flex">
      <Card
        v-for="(element, index) in comics"
        :key="index"
        :thumb="element.thumb"
        :price="element.price"
        :title="element.series"
        :type="element.type"
      />
    </div>
  </div>
</template>

<script>
import Card from './Card.vue';

export default {
  name: "Main",
  components: {
    Card,
  },
  props: {
    comics: Array,
  },
};
</script>

<style lang="scss" scoped>

.main-section {
  background-color: rgb(28, 28, 28);
  .container {
    height: 100%;
    flex-wrap: wrap;
    padding: 40px 0;
    .text-main {
      color: white;
      font-size: 20px;
      padding-top: 40px;
    }
  }
}
</style>