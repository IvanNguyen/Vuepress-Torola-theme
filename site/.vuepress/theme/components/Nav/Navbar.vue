<template>
  <header id="header">
    <!-- Logo -->
    <a href="index.html" class="logo">
      <img src="../../../public/images/logo-light.png" class="logo-light" alt="logo">
    </a>
    <!-- Navigation -->
    <Navigation/>
    <!-- /Navigation -->
  </header>
</template>

<script>
import Navigation from './Navigation.vue'
export default {
    components: { Navigation },
};
</script>

<style lang="scss">
#header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    /* position: relative; */
    position: fixed;
    top: 0;
    left: 0;
    /* box-sizing
    margin */
    border-bottom: 1px solid rgba(255,255,255,.08);
    width: 100%;
    height: 65px;
    padding: 0 50px;
    /* font-size
    line-height */
    background-color: black;
    z-index: 1001;
}
</style>