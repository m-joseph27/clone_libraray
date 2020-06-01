<template>
  <div class="carrouselWrapper">
    <div class="carousel"
      data-flickity='{ "wrapAround": true }'>
      <div class="carousel-cell">
        <img src="../assets/img/dilan.jpeg" alt="dilan">
        <div class="carousel-name">
          <header>Dilan 1990</header>
          <footer>Pidi Baiq</footer>
        </div>
      </div>
      <div class="carousel-cell">
        <img src="../assets/img/laskar.jpeg" alt="laskar-pelangi">
        <div class="carousel-name">
          <header>Laskar pelangi</header>
          <footer>Andrea Hirata</footer>
        </div>
      </div>
      <div class="carousel-cell">
        <img src="../assets/img/ubur-ubur.png" alt="ubur-ubur-lembur">
        <div class="carousel-name">
          <header>Ubur ubur Lembur</header>
          <footer>Raditya Dika</footer>
        </div>
      </div>
      <div class="carousel-cell">
        <img src="../assets/img/react.jpeg" alt="">
        <div class="carousel-name">
          <header>React Native</header>
          <footer>hoseph</footer>
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
  * { box-sizing: border-box; }

body { font-family: sans-serif; }

.carousel {
  background: rgb(255, 255, 255);
}

.carousel-cell {
  width: 40%;
  height: 300px;
  margin-right: 40px;
  box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.267);
  background: #8C8;
  border-radius: 15px;
  overflow: hidden;
  display: flex;
  align-items: flex-end;
  position: relative;
  img{
    object-fit: cover;
    width: 100%;
    height: 100%;
    object-position: center;
  }
  .carousel-name{
    background-color: rgba(0, 0, 0, 0.281);
    position: absolute;
    width: 100%;
    height: 40%;
    display: flex;
    padding-left: 40px;
    flex-direction: column;
    justify-content: center;
    header{
      color: white;
      font-size: 25px;
      font-weight: bold;
    }
    footer{
      color: white;
      font-size: 15px;
      font-weight: 500;
    }
  }
}

/* cell number */
.carousel-cell:before {
  display: block;
  text-align: center;
  line-height: 200px;
  font-size: 80px;
  color: white;
}
</style>
