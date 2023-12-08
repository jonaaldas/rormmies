<template>
    <div class="overflow-x-hidden bg-base-100 font-body text-sm text-base-content antialiased">
        <NavBar />
        <Hero />
        <Trifold />
    </div>
</template>

<script>
    import Hero from '../components/landing_page/Hero.vue';
    import NavBar from '../components/landing_page/NavBar.vue';
    import Trifold from '../components/landing_page/Trifold.vue';
    export default {
        components: {Hero, NavBar, Trifold},
    };
</script>

<style></style>
``