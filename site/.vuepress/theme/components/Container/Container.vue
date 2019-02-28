<template>
    <main id="main" class="bg-lines" style="padding-top: 65px;">
        <HeaderBaner></HeaderBaner>
        <About></About>
        <Portfolio></Portfolio>
        <Cta></Cta>
        <Home></Home>
    </main>
</template>

<script>
import Home from '../../pages/Home.vue'
import HeaderBaner from '../../global-components/HeaderBaner.vue'
import About from '../../global-components/About.vue'
import Portfolio from '../../global-components/Portfolio.vue'
import Cta from '../../global-components/Cta.vue'
    export default {
        components: { Home, HeaderBaner, About, Portfolio, Cta },
    }
</script>

<style scoped>

</style>