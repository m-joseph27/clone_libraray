<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="navbar">
      <!-- <div class="sidebarSide"></div> -->
      <button class="navbar-toggler" type="button"
      data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup"
      aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="sidebarSide">
          <img src="../assets/img/icons8-menu-24.png" alt="menu">
        </div>
        <div class="search"></div>
        <div class="action-button">
          <button>Login</button>
          <button>Register</button>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.navbar{
  // background-color: burlywood;
  position: fixed;
  width: 100%;
  height: 60px;
  .sidebarSide{
    width: 50px;
    height: 50px;
    // background-color: cadetblue;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .search{
    width: 500px;
    height: 50px;
    background-color: chocolate;
    position: absolute;
    left: 300px;
    top: 5px;
  }
  .action-button{
    // width: 200px;
    // height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
    right: 40px;
    button{
      width: 90px;
      height: 40px;
      margin: 0 5px;
    }
  }
}
</style>
