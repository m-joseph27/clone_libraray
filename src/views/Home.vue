<template>
  <div class="home">
    <navbar/>
    <sidebar/>
    <jumbotron/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import Navbar from '../components/Navbar.vue';
// import Sidebar from '../components/Sidebar.vue';
import Jumbotron from '../components/Jumbotron.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    Navbar,
    // Sidebar,
    Jumbotron,
  },
};
</script>

<style lang="scss" scoped>

</style>
