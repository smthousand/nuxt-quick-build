<template>
    <nav id="nav" role="nav">
        <div class="nav__main-menu">
            <ul class="nav__main-items">
                <li @click="" class="nav__main-item"><img src="~/assets/images/menu_icons/1.svg" alt=""></li>
                <li @click="" class="nav__main-item"><img src="~/assets/images/menu_icons/2.svg" alt=""></li>
                <li @click="" class="nav__main-item"><img src="~/assets/images/menu_icons/3.svg" alt=""></li>
                <li @click="" class="nav__main-item"><img src="~/assets/images/menu_icons/4.svg" alt=""></li>
                <li @click="" class="nav__main-item"><img src="~/assets/images/menu_icons/5.svg" alt=""></li>
                <li @click="" class="nav__main-item"><img src="~/assets/images/menu_icons/6.svg" alt=""></li>
            </ul>
        </div>
        <!-- <div class="nav__sub-menu">
            <ul>
                <li>dd</li>
                <li>dd</li>
                <li>dd</li>
            </ul>
        </div> -->
    </nav>
</template>

<script setup>

</script>

<style lang="scss" scoped>
#nav {
    min-height: calc(100vh - 57px);
    display: flex;
    .nav__main-menu {
        background-color: $secondary;
        padding: $x12 $x4;
        ul {
            display: flex;
            flex-direction: column;
            gap: $x2;
            li {
                padding: $x3;
                border-radius: $x3;
                &:hover, &.active {
                    background-color: #1b1d38;
                }
            }
        }
    }
    .nav__2depth {
        border-right: 1px solid $gray-200;
    }
}
</style>