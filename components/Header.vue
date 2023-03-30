<template>
    <header id="header" role="header">
        <div class="header__info">
            <p class="header__class">Digital SAT Int (A) (온&오프)</p>
            <p class="header__user">
                김현수<span> 학생</span>

                <ul class="header__info-list">
                        <a href="">
                            <li>
                                <img src="~/assets/images/icons/my_information.svg" alt="">
                                My Information
                            </li>
                        </a>
                        <a href="">
                            <li>
                                <img src="~/assets/images/icons/logout.svg" alt="">
                                Logout
                            </li>
                        </a>
                </ul>
            </p>
        </div>
    </header>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>
        #header {
            width: 100%;
            border-bottom: 1px solid $gray-200;
            padding: $x4 $x10;
            background-color: $white;
            display: flex;
            justify-content: flex-end;
            align-items: center;

            position: sticky;
            top: 0;
            left: 0;
            // z-index: 2;
            .header__info {
                display: flex;
                justify-content: flex-start;
                align-items: center;
                gap: $x3;
                .header__class {
                    font-size: $x3;
                    color: $gray-400;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    gap: $x3;
                    &::after {
                        content: "";
                        width: 3px;
                        height: 3px;
                        background-color: $gray-300;
                        display: inline-block;
                    }
                }
                .header__user {
                    color: $gray-500;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    gap: $x1;
                    &::after {
                        content: "";
                        width: $x6;
                        height: $x6;
                        background: url('~/assets/images/icons/arrow_down.svg') no-repeat center;
                        display: inline-block;
                    }
                    &:hover {
                        .header__info-list {
                            display: block;
                        }
                        &::after {
                            content: "";
                            background: url('~/assets/images/icons/arrow_up.svg') no-repeat center;
                        }
                    } 
                }
            }
        }

        .header__info-list {
            display: none;
            position: absolute;
            top: $x12;
            right: $x10;
            background-color: $white;
            border: 1px solid $gray-200;
            border-radius: $x1;
            max-width: 500px;
            box-shadow: rgba(149, 157, 165, 0.2) 0px 8px 24px;
            a {
                text-decoration: none;
                color: $gray-500;
                li {
                    display: flex;
                    justify-content: flex-start;
                    align-items: center;
                    gap: $x2;
                    padding: $x3 $x6;
                    &:hover {
                        background-color: $gray-100;
                    }
                }
            }
        }

</style>