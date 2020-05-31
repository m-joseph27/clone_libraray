<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button"
    data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup"
    aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <a class="nav-item nav-link active" href="#">Home <span class="sr-only">(current)</span></a>
      <a class="nav-item nav-link" href="#">Features</a>
      <a class="nav-item nav-link" href="#">Pricing</a>
      <a class="nav-item nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
    </div>
  </div>
</nav>
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
    input{
      width: 400px;
      height: 35px;
      border-radius: 3px;
      outline: none;
      border: 1px solid rgba(0, 0, 0, 0.233);
      padding: 0 40px;
    }
    .input-icon{
      position: relative;
      .fas{
        position: absolute;
        top: 10px;
        left: 15px;
      }
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
      font-size: 13px;
      font-weight: 700;
      text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.233);
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
