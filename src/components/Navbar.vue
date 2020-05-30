<template>
  <div class="navbarWrapper">
    <div class="sidebar">
      <img src="../assets/img/icons8-menu-24.png" width="20px" height="20px" alt="menu">
    </div>
    <div class="search" style="max-width:400px;margin:auto">
      <div class="input-icons">
        <!-- <i class="fas fa-search"></i> -->
        <input class="input-field" type="text">
      </div>
    </div>
    <div class="btn-nav">
      <button class="btn-login">Login</button>
      <button class="btn-reg">Register</button>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.navbarWrapper{
  background-color: rgb(255, 255, 255);
  width: 100%;
  height: 50px;
  display: flex;
  box-shadow: 1px 1px 1px rgba(0, 0, 0, 0.322);
  justify-content: space-between;
  position: fixed;
  top: 0;
  z-index: 5;
  .sidebar{
    width: 70px;
    height: 100%;
    // background-color: rosybrown;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
  }
  .search{
    // width: 450px;
    height: 100%;
    // background-color: royalblue;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    input{
      width: 400px;
      height: 35px;
      border-radius: 3px;
      outline: none;
      border: 1px solid rgba(0, 0, 0, 0.233);
      padding: 0 20px;
    }
  }
  .btn-nav{
    width: 300px;
    height: 100%;
    // background-color: salmon;
    display: flex;
    justify-content: center;
    align-items: center;
    button{
      width: 90px;
      height: 35px;
      margin: 0 10px;
      border-radius: 3px;
      border: none;
      outline: none;
      cursor: pointer;
    }
    .btn-login{
      background-color: rgb(255, 255, 255);
      border: 1px solid rgba(0, 0, 0, 0.623);
      color: rgba(0, 0, 0, 0.623);
      }
      .btn-reg{
        background-color: cadetblue;
        color: white;
        font-size: 13px;
        font-weight: 700;
        text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.233);
      }
  }
}

</style>
