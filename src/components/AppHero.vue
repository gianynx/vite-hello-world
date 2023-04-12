<template>
    <div>
        <div class="hero-image"></div>
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                btnText: 'Click me!'
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