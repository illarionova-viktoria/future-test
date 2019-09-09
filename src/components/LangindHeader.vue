<template>
  <div class="header">
    <div class="header-logo">
      <img src="../assets/Vector.png">
    </div>
    <div class="header-number">
      <div class="header-number-text">Телефон:</div>
      <a class="header-number-num" href="#">8(800)-123-12-12</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'LangindHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header {
  position: absolute;
  width: 1920px;
  height: 100px;
  left: 0px;
  top: 0px;
  background: #FFFFFF;

  &-logo {
    position: absolute;
    width: 129px;
    height: 23px;
    left: 390px;
    top: 39px;
  }

  &-number {

    &-text {
      position: absolute;
      width: 66px;
      height: 18px;
      left: 555px;
      top: 41px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;

      color: #B3B3B3;
    }

    &-num {
      position: absolute;
      width: 108px;
      height: 18px;
      left: 621px;
      top: 41px;

      font-family: Montserrat;
      font-style: normal;
      font-weight: normal;
      font-size: 14px;
      line-height: 17px;
      text-decoration: none;

      color: #37373F;
    }
  }
}
</style>
