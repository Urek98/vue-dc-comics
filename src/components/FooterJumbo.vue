<template>
  <div class="footer-jumbo">
    <div class="container flex">
      <div class="flex">
        <ul>
          <li><h2>DC COMICS</h2></li>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
          <li><h2>DC COMICS</h2></li>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
        <ul>
          <li><h2>DC</h2></li>
          <li>Terms Of Use</li>
          <li>Privacy policy(New)</li>
          <li>Ad Choices</li>
          <li>Advertising</li>
          <li>Jobs</li>
          <li>Subscriptions</li>
          <li>Talent Workshops</li>
          <li>CPSC Certificates</li>
          <li>Ratings</li>
          <li>Shop Help</li>
          <li>Contact Us</li>
        </ul>
        <ul>
          <li><h2>SITES</h2></li>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
      <div>
        <img src="../assets/dc-logo-bg.png" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterJumbo",
};
</script>


<style lang="scss" scoped>
.footer-jumbo {
  height: 330px;
  background-image: url(../assets/footer-bg.jpg);
  color: white;
  .container {
    justify-content: space-between;
    align-items: center;
    ul {
        padding-right: 10px;
      h2 {
        padding: 10px 0;
        color: white;
      }
      li {
        font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
          Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
        font-size: 12px;
        color: rgb(100, 134, 134);
      }
    }
      img {
        width: 400px;
        position: relative;
        z-index: 1;
      }
  }
}
</style>