<template>
  <div class="jumbotron jumbotron-fluid">
  <div class="container">
    <h1 class="display-4">Welcome to Library app</h1>
  </div>
</div>
</template>

<script>
export default {

};
</script>

<style lang="scss" scoped>
  .jumbotron{
    width: 100%;
    height: 500px;
    background-image:linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url('../assets/img/library.jpg');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    .container{
      display: flex;
      justify-content: center;
      align-items: center;
      h1{
        color: white;
        padding: 200px 0;
        text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.7);
      }
    }
  }
</style>
