<template>
  <div class="loginWrapper">
    <div class="leftSide"></div>
    <div class="rightSide">
    </div>
  </div>
</template>

<script>
export default {

};

</script>

<style lang="scss" scoped>
.loginWrapper{
  width: 100vw;
  height: 100vh;
  background-color: rgb(58, 58, 58);
  display: flex;
  .leftSide{
    width: 55%;
    height: 100%;
    // background-color: #fff;
    background-image: url('../assets/img/background.jpeg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
  }
  .rightSide{
    width: 45%;
    height: 100%;
    background-color: rgb(255, 255, 255);
  }
}

</style>
