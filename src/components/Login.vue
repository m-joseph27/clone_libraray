<template>
  <div class="loginWrapper">
    <div class="leftSide">
      <header>hello</header>
    </div>
    <div class="rightSide">
      <div class="topSide"></div>
      <div class="midSide"></div>
      <div class="formSide"></div>
      <div class="bottomSide"></div>
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
    background-image:linear-gradient(rgba(0, 0, 0, 0.3),
    rgba(0, 0, 0, 0.3)) ,url('../assets/img/background.jpeg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
  }
  .rightSide{
    width: 45%;
    height: 100%;
    background-color: rgb(255, 255, 255);
    display: flex;
    flex-direction: column;
    .topSide{
      width: 100%;
      height: 90px;
      background-color: aquamarine;
    }
    .midSide{
      width: 100%;
      height: 130px;
      background-color: blueviolet;
    }
    .formSide{
      width: 100%;
      height: 300px;
      background-color: burlywood;
    }
  }
}

</style>
