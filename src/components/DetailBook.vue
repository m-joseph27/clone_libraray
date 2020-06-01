<template>
  <div class="detailWrapper">
    <div class="jumbotron jumbotron-fluid">
      <div class="navDetail">
        <router-link to="/">
        <div class="btn-back">
          <img src="../assets/img/left-arrow.png" alt="left-arrow">
        </div>
        </router-link>
        <div class="btn-book">
          <ul>
            <li>Edit</li>
            <li>Delete</li>
          </ul>
        </div>
      </div>
      <!-- <img src="../assets/img/ubur-ubur.png" alt="jumbotron-image"> -->
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.detailWrapper{
  display: flex;
  flex-direction: column;
  width: 100%;
  height: 1000px;
  background-color: rgba(0, 0, 0, 0.13);
  .jumbotron{
    position: relative;
    width: 100%;
    height: 600px;
    background-image: url('../assets/img/ubur-ubur.png');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    opacity: .9;
    .navDetail{
      position: absolute;
      top: 0;
      width: 100%;
      height: 80px;
      // background-color: burlywood;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      align-items: center;
      .btn-back{
        background-color: rgb(255, 255, 255);
        width: 60px;
        height: 60px;
        border-radius: 100%;
        margin-left: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
        img{
          object-fit: cover;
          width: 50%;
          height: 50%;
        }
      }
      .btn-book{
        // background-color: chocolate;
        width: 200px;
        height: 60px;
        ul{
          list-style: none;
          display: flex;
          color: white;
          font-size: 20px;
          font-weight: bold;
          li{
            width: 60px;
          }
        }
      }
    }
  }
}
</style>
