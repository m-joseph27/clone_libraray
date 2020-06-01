<template>
  <div class="itemWrapper">
    <div class="listItem">
      <h3>List Book</h3>
    </div>
    <div class="listContent">
      <div class="cardList">
        <div class="cardImage">
          <img src="../assets/img/dilan.jpeg" alt="cardImage">
        </div>
        <div class="cardName">
          <header>Dilan 1990</header>
          <footer>Lorem ipsum dolor,
            sit amet consectetur
            adipisicing elit. Aut,
            cupiditate voluptate
            saepe ratione quidem quo
            temporibus</footer>
        </div>
      </div>
      <div class="cardList">
        <div class="cardImage">
          <img src="../assets/img/ubur-ubur.png" alt="cardImage">
        </div>
        <div class="cardName">
          <header>Dilan 1990</header>
          <footer>Lorem ipsum dolor,
            sit amet consectetur
            adipisicing elit. Aut,
            cupiditate voluptate
            saepe ratione quidem quo
            temporibus</footer>
        </div>
      </div>
      <div class="cardList">
        <div class="cardImage">
          <img src="../assets/img/laskar.jpeg" alt="cardImage">
        </div>
        <div class="cardName">
          <header>Dilan 1990</header>
          <footer>Lorem ipsum dolor,
            sit amet consectetur
            adipisicing elit. Aut,
            cupiditate voluptate
            saepe ratione quidem quo
            temporibus</footer>
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
.itemWrapper{
  width: 100%;
  // height: 600px;
  // background-color: rgb(70, 102, 83);
  margin: 50px 0;
  .listItem{
    // background-color: rgb(22, 22, 22);
    width: 100%;
    height: 10%;
    padding-left: 60px;
    h3{
      font-weight: 600;
    }
  }
  .listContent{
    width: 100%;
    height: 90%;
    // background-color: burlywood;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    .cardList{
      width: 320px;
      height: 340px;
      background-color: #fff;
      box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.25);
      border-radius: 15px;
      margin: 40px 20px;
      overflow: hidden;
      .cardImage{
        width: 100%;
        height: 200px;
        background-color: rgba(0, 0, 0, 0.25);
        img{
          object-fit: cover;
          width: 100%;
          height: 100%;
          object-position: center;
        }
      }
      .cardName{
        width: 100%;
        height: 140px;
        background-color: rgb(255, 255, 255);
        text-align: center;
        overflow: hidden;
        header{
          font-size: 20px;
          font-weight: 600;
          line-height:50px;
        }
      }
    }
  }
}
</style>
