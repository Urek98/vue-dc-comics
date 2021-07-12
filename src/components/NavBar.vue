<template>
  <div class="container">
    <div class="nav-bar">
      <div>
        <img src="../assets/dc-logo.png" alt="" />
      </div>
      <div class="nav-elements">
        <ul>
          <li>CHARACTERS</li>
          <li>COMICS</li>
          <li>MOVIES</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>COLLECTIBLES</li>
          <li>VIDEOS</li>
          <li>FANS</li>
          <li>NEWS</li>
          <li>SHOP</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
};
</script>

<style lang="scss" scoped>
.nav-bar {
  display: flex;
  justify-content: space-between;
  height: 110px;
  .nav-elements {
    ul {
      list-style: none;
      display: flex;
      align-items: center;
      height: 100%;
      li {
        margin: 0 5px;
        height: 100%;
        padding-top: 40px;
        font-size: 12px;
        cursor: pointer;

        &:hover{
            color: rgb(4,121,230);
            border-bottom: 3px solid rgb(4,121,230);
        }
      }
    }
  }
}
</style>