<template>
    <div class="wrap">
        <Header />
        <div class="main">
            <Nav />
            <Nuxt />
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
    .main {
        // margin-top: 66px;
        height: calc(100vh - 66px);
        display: flex;
    }
</style>