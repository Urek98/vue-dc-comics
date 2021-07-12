<template>
  <div class="main-section">
      <div class="container">
          <div class="text-main">
            --Contents Goes here--
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: "Main",
};
</script>

<style lang="scss" scoped>
    .main-section{
        background-color: rgb(28,28,28);
        height: 120px;
        .container{
            height: 100%;
            .text-main{
                color: white;
                font-size: 20px;
                padding-top: 40px;
            }
        }
    }
</style>