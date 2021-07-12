<template>
  <div class="footer-section">
    <div class="icon-section">
      <div class="container flex">
        <div class="flex">
            <img src="../assets/buy-comics-digital-comics.png" alt="">
            <div>DIGITAL COMICS</div>
        </div>
        <div class="flex">
            <img src="../assets/buy-comics-merchandise.png" alt="">
            <div>DC MERCHANDISE</div>
        </div>
        <div class="flex">
            <img src="../assets/buy-comics-shop-locator.png" alt="">
            <div>COMIC SHOP LOCATOR</div>
        </div>
        <div class="flex">
            <img src="../assets/buy-comics-subscriptions.png" alt="">
            <div>SUBSCRIPTIONS</div>
        </div>
        <div class="flex">
            <img src="../assets/buy-dc-power-visa.svg" alt="">
            <div>DC POWER VISA</div>
        </div>
      </div>
    </div>
    <div class="footer-jumbo"></div>
    <div class="footer-end"></div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.footer-section {
  background-color: rgb(28, 28, 28);
  height: 470px;
  .icon-section {
    height: 120px;
    background-color: rgb(2, 130, 249);
    .container{
        justify-content: space-between;
        align-items: center;
        img {
            height:40px;
        }
        div {
            color: white;
            padding-left: 10px;
            align-items: center;
            font-size: 12px;
        }
    }
  }
}
</style>