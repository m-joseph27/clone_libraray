<template>
  <div class="home">
    <navbar />
    <sidebar />
    <jumbotron />
    <carrousel />
    <item />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import Navbar from '../components/Navbar.vue';
// import Sidebar from '../components/Sidebar.vue';
import Jumbotron from '../components/Jumbotron.vue';
import Carrousel from '../components/Carrousel.vue';
import Item from '../components/Item.vue';

export default {
  name: 'Home',
  components: {
    // HelloWorld,
    Navbar,
    // Sidebar,
    Jumbotron,
    Carrousel,
    Item,
  },
};
</script>

<style>

</style>
