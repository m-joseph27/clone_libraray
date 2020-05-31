<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  watch: {
    $route: {
      handler: (to) => {
        document.title = to.meta.title || 'Library app';
      },
      immediate: true,
    },
  },
};
</script>

<style>
html, body{
  margin: 0;
}

#app {
  color: #2c3e50;
}
</style>
