<template>
  <div class="icon-section">
    <div class="container flex">
      <div class="flex">
        <img src="../assets/buy-comics-digital-comics.png" alt="" />
        <div>DIGITAL COMICS</div>
      </div>
      <div class="flex">
        <img src="../assets/buy-comics-merchandise.png" alt="" />
        <div>DC MERCHANDISE</div>
      </div>
      <div class="flex">
        <img src="../assets/buy-comics-shop-locator.png" alt="" />
        <div>COMIC SHOP LOCATOR</div>
      </div>
      <div class="flex">
        <img src="../assets/buy-comics-subscriptions.png" alt="" />
        <div>SUBSCRIPTIONS</div>
      </div>
      <div class="flex">
        <img src="../assets/buy-dc-power-visa.svg" alt="" />
        <div>DC POWER VISA</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterIcon",
};
</script>

<style lang="scss" scoped>
.icon-section {
  height: 120px;
  background-color: rgb(2, 130, 249);
  .container {
    justify-content: space-around;
    align-items: center;
    img {
      height: 40px;
    }
    div {
      color: white;
      padding-left: 10px;
      align-items: center;
      font-size: 12px;
    }
  }
}
</style>