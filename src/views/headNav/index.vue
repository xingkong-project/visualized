<template>
  <header class="header flex f-jc-sb wh">
    <div class="header-left">
      <a href="" class="db flex f-ai-c">
        <img src="https://s10.mogucdn.com/mlcdn/c45406/191228_30he6jggj4i4c6ck91f9hef888ejh_400x400.png" alt="" class="db">
        <span>星空</span>
      </a>
    </div>
    <div class="header-right flex f-ai-c">
      <img src="https://s10.mogucdn.com/mlcdn/c45406/191228_50h0l03k4hikdfek519cf332j6ge7_959x959.jpg" alt="" class="db">
      <span>接水怪</span>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="less" scoped>
  .header {
    height: 45px;
    padding: 0 5%;
    background-color: #545c64;
    &-left {
      a {
        height: 45px;
        img {
          width: 30px;
          margin-right: 5px;
        }
      }
    }
    &-right {
      img {
        width: 30px;
        border-radius: 50%;
        margin-right: 5px;
      }
    }
  }
</style>
