<template>
  <div class="home">
    <navbar/>
    <sidebar/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import Navbar from '../components/Navbar.vue';
import Sidebar from '../components/Sidebar.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    Navbar,
    Sidebar,
  },
};
</script>

<style lang="scss" scoped>

</style>
