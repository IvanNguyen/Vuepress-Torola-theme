<template>
    <main id="main" class="bg-lines" style="padding-top: 65px;">
        <HeaderBaner></HeaderBaner>
        <About></About>
        <Portfolio></Portfolio>
        <Home></Home>
    </main>
</template>

<script>
import Home from '../../pages/Home.vue'
import HeaderBaner from '../../global-components/HeaderBaner.vue'
import About from '../../global-components/About.vue'
import Portfolio from '../../global-components/Portfolio.vue'
    export default {
        components: { Home, HeaderBaner, About, Portfolio },
    }
</script>

<style scoped>

</style>