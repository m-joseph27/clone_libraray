<template>
  <div class="detailWrapper">
    <div class="jumbotron jumbotron-fluid">
      <div class="navDetail">
        <a href="/">
        <div class="btn-back">
          <img src="../assets/img/left-arrow.png" alt="left-arrow">
        </div>
        </a>
        <div class="btn-book">
          <ul>
            <li>Edit</li>
            <li>Delete</li>
          </ul>
        </div>
      </div>
      <div class="book"></div>
    </div>
    <div class="container">
      <div class="content-detail">
        <div class="content-badge"><p>Novel</p></div>
        <div class="content-name"><p>DILAN 1990</p>
        <h2>Avaliable</h2></div>
        <div class="content-date"><p>30 JUNI 2019</p></div>
        <div class="content-description">
          <div class="description-book">
            <p>Lorem ipsum dolor sit,
              amet consectetur adipisicing
              elit. Iste earum sit nobis,
              sunt velit, cum natus beatae perferendis ipsum porro
              incidunt quo, explicabo placeat alias dolore id fugit est odit.
              Lorem ipsum dolor sit
              amet consectetur adipisicing
              elit. Perferendis doloribus,
              nam sit ducimus asperiores
              nemo sint? Labore neque ex in,
              fuga maxime mollitia repellendus aperiam odit officiis veritatis quam vel.
              Lorem ipsum dolor sit
              amet consectetur adipisicing
              elit. Soluta quia ipsam
              iste accusantium dolorem.
              Incidunt, dicta earum
              pariatur itaque iure
              odit consectetur harum! Hic vero libero inventore nemo voluptates saepe?</p>
          </div>
          <div class="btn-description">
            <button>Borrow</button>
          </div>
        </div>
      </div>
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
  // height: 1200px;
  background-color: rgb(255, 255, 255);
  margin-bottom: 40px;
  .jumbotron{
    position: relative;
    width: 100%;
    height: 600px;
    background-image: url('../assets/img/ubur-ubur.png');
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    opacity: .9;
    background-attachment: fixed;
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
    .book{
      width: 200px;
      height: 288.81px;
      background-color: rgb(255, 255, 255);
      position: absolute;
      z-index: 2;
      bottom: -100px;
      right: 50px;
      box-shadow: 0px 6px 20px rgba(0, 0, 0, 0.25);
      border-radius: 15px;
      background-image: url('../assets/img/ubur-ubur.png');
      background-size: cover;
      background-position: center;
    }
  }
  .content-detail{
    width: 100%;
    // height: 600px;
    background-color: rgb(255, 255, 255);
    display: flex;
    flex-direction:column;
    .content-badge{
      width: 120px;
      height: 40px;
      border-radius: 60px;
      background: #FBCC38;
      p{
        text-align: center;
        padding: 7px 0;
        color: white;
        font-size: 18px;
        font-weight: bold;
      }
    }
    .content-name{
      // background-color: burlywood;
      width: 70%;
      height: 60px;
      margin-top: 7px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      p{
        font-weight: bold;
        font-size: 50px;
      }
      h2{
        font-weight: bold;
        color: #99D815;
      }
    }
    .content-date{
      width: 200px;
      height: 40px;
      // background-color: cadetblue;
    }
    .content-description{
      width: 100%;
      // height: 400px;
      // background-color: chartreuse;
      display: flex;
      flex-direction: row;
      justify-content: space-between;
      .description-book{
        width: 70%;
        height: 100%;
        // background-color: wheat;
        padding-top: 20px;
      }
      .btn-description{
        width: 20%;
        height: 100%;
        // background-color: rgb(145, 192, 172);
        display: flex;
        justify-content: center;
        align-items: flex-end;
        button{
          width: 240px;
          height: 60px;
          background: #FBCC38;
          box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
          border-radius: 10px;
          border: 0;
          outline: none;
          color: white;
          font-weight: bold;
          font-size: 18px;
        }
      }
    }
  }
}
</style>
