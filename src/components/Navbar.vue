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
          <i class="far fa-search"></i>
          <img src="../assets/img/icons8-menu-24.png" alt="menu">
        </div>
        <div class="search">
          <input type="text" placeholder="Search here">
        </div>
        <div class="action-button">
          <button class="btn-login">Login</button>
          <button class="btn-reg">Register</button>
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
.navbar-expand-lg{
  background-color: yellowgreen;
}
.navbar{
  position: fixed;
  width: 100%;
  height: 60px;
  box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.103);
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
    // background-color: chocolate;
    position: absolute;
    left: 300px;
    top: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
    input{
      width: 400px;
      height: 40px;
      outline: none;
      padding-left: 50px;
      border: 1px solid rgba(0, 0, 0, 0.295);
      border-radius: 3px;
    }
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
      height: 35px;
      margin: 0 5px;
      border-radius: 3px;
      cursor: pointer;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
      font-weight: 600;
    }
    .btn-login{
      color: rgba(0, 0, 0, 0.801);
      border:  1px solid rgba(0, 0, 0, 0.603);
      background-color: white;
    }
    .btn-reg{
      color: whitesmoke;
      background-color: cadetblue;
      outline: none;
      border: none;
    }
  }
}
</style>
