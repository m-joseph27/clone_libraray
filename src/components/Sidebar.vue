<template>
  <div class="SidebarWrapper">
    <div class="sidebarParent">
      <div class="topSide" @click="$emit('left-arrow')">
        <i class="fas fa-chevron-left"></i>
      </div>
      <div class="profileSide">
        <header> <img src="../assets/img/foto-cv.jpg" alt="profile-pic"></header>
        <footer><h3>Muhammad Yusuf</h3></footer>
      </div>
      <div class="menuSide">
        <ul>
          <li>Explore</li>
          <li>History</li>
          <li>Add Book*</li>
          <li>Logout</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>

.SidebarWrapper.sideActive{
  left: 0;
  position: fixed;
  z-index: 99;
  visibility: visible;
}

.SidebarWrapper{
  width: 100vw;
  height: 100vh;
  background-color: rgba(0, 0, 0, 0.4);
  position: fixed;
  top: 0;
  z-index: 6;
  visibility: hidden;
  transition: ease-in .1s;
  .sidebarParent{
    width: 400px;
    height: 100vh;
    background: rgb(255, 255, 255);
    box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.301);
    // display: flex;
    overflow: hidden;
    .topSide{
      background-color: rgb(255, 255, 255);
      width: 100%;
      height: 60px;
      box-shadow: 0 1px 0 rgba(0, 0, 0, 0.301);
      display: flex;
      justify-content: flex-end;
      padding-right: 30px;
      align-items: center;
      box-sizing: border-box;
      &:active{
        transform: translateX(2px);
      }
      i{
        font-size: 20px;
        cursor: pointer;
      }
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
        margin: 15px 0;
        img{
          object-fit: cover;
          height: 100%;
          width: 100%;
          object-position: center;
        }
      }
    }
    .menuSide{
      width: 100%;
      // height: 140px;
      li{
        padding-top: 30px;
        list-style: none;
        height: 40px;
      }
    }
  }
}

</style>
