<template>
    <AppTitle />
    <div>
        <div class="hero-image"></div>
    </div>
</template>

<script>
    import AppTitle from './AppTitle.vue';
    export default {
        name: 'AppHero',
        data() {
            return {
                
            }
        }
    }
</script>

<style lang="scss" scoped>

.hero-image {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url("../assets/img/jumbo.jpg");
    height: 50%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
}

</style>