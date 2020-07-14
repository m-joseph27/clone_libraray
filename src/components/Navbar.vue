<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="navbar">
      <button class="navbar-toggler" type="button"
      data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup"
      aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="sidebarSide" @click="$emit('nav-clicked',$event.target)">
          <img src="../assets/img/icons8-menu-24.png" alt="menu">
        </div>
        <div class="content-sort">
          <select name="All Categories" id="">
            <option value="">All Categories</option>
            <option value="">Novel</option>
            <option value="">Comic</option>
          </select>
          <select name="All Time" id="">
            <option value="">All Times</option>
            <option value="">2020</option>
            <option value="">2019</option>
            <option value="">2018</option>
          </select>
        </div>
        <div class="search">
          <input type="text" placeholder="Search here">
          <img src="../assets/img/search.png" width="25px" height="25px" alt="search">
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
  z-index: 5;
  .sidebarSide{
    width: 50px;
    height: 50px;
    // background-color: cadetblue;
    display: flex;
    justify-content: center;
    align-items: center;
    &:active{
      transform: translateY(2px)
    }
    cursor: pointer;
  }
  .content-sort{
    // width: 200px;
    height: 30px;
    // background-color: blueviolet;
    position: absolute;
    left: 120px;
    select{
      width: 120px;
      margin: 0 5px;
      font-size: 12px;
      font-weight: 600;
      border: none;
      outline: none;
      background-color: #F8F9FA;
      cursor: pointer;

    }
  }
  .search{
    width: 500px;
    height: 40px;
    // background-color: chocolate;
    position: relative;
    left: 350px;
    top: -3px;
    display: flex;
    justify-content: center;
    align-items: center;
    input{
      width: 100%;
      height: 100%;
      outline: none;
      padding-left: 50px;
      border: 1px solid rgba(0, 0, 0, 0.295);
      border-radius: 3px;
    }
    img{
      position: absolute;
      left: 15px;
      top: 8px;
      opacity: .8;
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
