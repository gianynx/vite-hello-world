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
</style>