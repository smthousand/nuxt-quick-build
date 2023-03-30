<template>
    <div class="wrap">
        <Header />
        <div class="container">
            <Nav />
            <Nuxt />
        </div>
    </div>
</template>

<script>
    export default {
        name: 'default'
    }
</script>

<style lang="scss" scoped>
.wrap {
    width: 100%;
    height: 100%;
    .container {
        margin-top: 66px;
        display: flex;
    }
}
</style>