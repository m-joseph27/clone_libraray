<template>
  <div class="carrouselWrapper">
    <div class="carousel"
      data-flickity='{ "wrapAround": true }'>
      <div class="carousel-cell"></div>
      <div class="carousel-cell"></div>
      <div class="carousel-cell"></div>
      <div class="carousel-cell"></div>
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
  background: #EEE;
}

.carousel-cell {
  width: 50%;
  height: 300px;
  margin-right: 10px;
  background: #8C8;
  border-radius: 5px;
  counter-increment: carousel-cell;
}

/* cell number */
.carousel-cell:before {
  display: block;
  text-align: center;
  content: counter(carousel-cell);
  line-height: 200px;
  font-size: 80px;
  color: white;
}
</style>
