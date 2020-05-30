<template>
  <div class="SidebarWrapper">
    <div class="sidebarParent">
      <div class="topSide">
        <i class="fas fa-chevron-left"></i>
      </div>
      <div class="profileSide"></div>
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
  z-index: 6;
  display: flex;
  .sidebarParent{
    width: 400px;
    height: 100vh;
    background: rgb(255, 255, 255);
    box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.301);
    display: flex;
    .topSide{
      background-color: rgb(255, 255, 255);
      width: 100%;
      height: 50px;
      box-shadow: 0 1px 0 rgba(0, 0, 0, 0.301);
    }
  }
}

</style>
