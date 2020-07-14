<template>
  <div class="home">
    <navbar @nav-clicked="sideBar" />
    <jumbotron />
    <carrousel />
    <item />
    <sidebar @left-arrow="hideModal"/>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue';
import Jumbotron from '../components/Jumbotron.vue';
import Carrousel from '../components/Carrousel.vue';
import Item from '../components/Item.vue';
import Sidebar from '../components/Sidebar.vue';

export default {
  name: 'Home',
  components: {
    Navbar,
    Jumbotron,
    Carrousel,
    Item,
    Sidebar,
  },
  methods: {
    sideBar() {
      document.querySelector('.SidebarWrapper').classList.add('sideActive');
    },
    hideModal() {
      document.querySelector('.SidebarWrapper').classList.remove('sideActive');
    },
  },
};
</script>

<style>

</style>
