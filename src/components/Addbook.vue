<template>
  <div class="addbookWrapper">
    <div class="addbookForm">
      <div class="topSide">
        <h4>Add Data</h4>
        <i class="fas fa-times"></i>
      </div>
      <div class="content">
        <div class="leftContent">
          <ul>
            <li>Url Image</li>
            <li>Title</li>
            <li>Description</li>
          </ul>
        </div>
        <div class="rightContent">
          <input type="text" placeholder="Url Image...">
          <input type="text" placeholder="Title...">
          <input class="text-area" type="text">
        </div>
      </div>
      <div class="bottomSide">
        <button class="btn-save">Save</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
.addbookWrapper{
  width: 100vw;
  height: 100vh;
  position: fixed;
  z-index: 6;
  background-color: rgba(0, 0, 0, 0.082);
  top: 0;
  left: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  .addbookForm{
    width: 700px;
    height: 500px;
    background-color: #fff;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.082);
    border-radius: 5px;
    overflow: hidden;
    .topSide{
      width: 100%;
      height: 15%;
      padding: 20px 30px;
      display: flex;
      justify-content: space-between;
      i{
        color: red;
        font-size: 30px;
        cursor: pointer;
      }
      h4{
        font-weight: bold;
      }
    }
    .content{
      width: 100%;
      height: 70%;
      // background-color: saddlebrown;
      display: flex;
      .leftContent{
        width: 25%;
        height: 100%;
        background-color: #fff;
        ul{
          list-style: none;
          padding-top: 20px;
          li{
            height: 70px;
            font-weight: 600;
          }
        }
      }
      .rightContent{
        // background-color: wheat;
        width: 75%;
        height: 100%;
        display: flex;
        flex-direction: column;
        input{
          width: 90%;
          height: 40px;
          margin: 12px 0;
          border-radius: 5px;
          outline: none;
          border: 1px solid rgba(0, 0, 0, 0.226);
          padding-left: 15px;
        }
        .text-area{
          height: 130px;
          padding-top: -200px;
        }
      }
    }
    .bottomSide{
      width: 100%;
      height: 15%;
      display: flex;
      justify-content: flex-end;
      padding-right: 20px;
      button{
        width: 120px;
        height: 45px;
        background: #FBCC38;
        border-radius: 10px;
        outline: none;
        border: none;
        color: white;
        font-weight: 600;
        font-size: 18px;
      }
    }
  }
}
</style>
