<template>
    <div>
        <header>
            <h1>{{ title }}</h1>
        </header>
    </div>
</template>

<script>
    export default {
        name: 'AppHeader',
        data() {
            return {
                title: 'La mia prima app con Vite!'
            }
        }
    }
</script>

<style lang="scss" scoped>
h1 {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
}
</style>