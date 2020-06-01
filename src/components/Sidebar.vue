<template>
  <div class="SidebarWrapper">
    <div class="sidebarParent">
      <div class="topSide">
        <i class="fas fa-chevron-left"></i>
      </div>
      <div class="profileSide">
        <header> <img src="../assets/img/foto-cv.jpg" alt="profile-pic"></header>
        <footer><h3>Muhammad Yusuf</h3></footer>
      </div>
      <div class="menuSide"></div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.SidebarWrapper{
  width: 100vw;
  height: 100vh;
  background-color: rgba(0, 0, 0, 0);
  position: relative;
  top: 0;
  z-index: 5;
  display: none;
  .sidebarParent{
    width: 400px;
    height: 100vh;
    background: rgb(255, 255, 255);
    box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.301);
    // display: flex;
    .topSide{
      background-color: rgb(255, 255, 255);
      width: 100%;
      height: 50px;
      box-shadow: 0 1px 0 rgba(0, 0, 0, 0.301);
      display: flex;
      justify-content: flex-end;
      padding-right: 30px;
      align-items: center;
      box-sizing: border-box;
      cursor: pointer;
    }
    .profileSide{
      width: 100%;
      height: 270px;
      // background-color: salmon;
      display: flex;
      justify-content: center;
      align-items: center;
      display: flex;
      flex-direction: column;
      header{
        width: 200px;
        height: 200px;
        background-color: rgb(0, 0, 0);
        border-radius: 100%;
        overflow: hidden;
        margin-top: 10px;
        img{
          object-fit: cover;
          height: 100%;
          width: 100%;
          object-position: center;
        }
      }
    }
  }
}

</style>
