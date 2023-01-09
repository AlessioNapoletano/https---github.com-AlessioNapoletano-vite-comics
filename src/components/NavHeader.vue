<script>
export default {
    data() {
        return {
            navList:
                [
                    {
                        text: "CHARACTERS",
                        active: false
                    },
                    {
                        text: "COMICS",
                        active: true
                    },
                    {
                        text: "MOVIES",
                        active: false
                    },
                    {
                        text: "TV",
                        active: false
                    },
                    {
                        text: "GAMES",
                        active: false
                    },
                    {
                        text: "COLLECTIBLES",
                        active: false
                    },
                    {
                        text: "VIDEOS",
                        active: false
                    },
                    {
                        text: "FANS",
                        active: false
                    },
                    {
                        text: "NEWS",
                        active: false
                    },
                    {
                        text: "SHOP",
                        active: false
                    },
                ]
        }
    }
}
</script>

<template>
    <header class="py-3">
        <div class="container-lg d-flex justify-content-between align-items-center">
            <div class="image-fluid">
                <img src="../assets/img/dc-logo.png" alt="DC comics Logo">
            </div>

            <nav>
                <ul>
                    <li v-for="item in navList" :class="(item.active) ? 'active' : ''">
                        {{ item.text }}
                    </li>
                </ul>
            </nav>
        </div>

    </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

ul {
    display: flex;

    li {
        padding: 1rem;
        font-weight: 600;
    }
}

.active {
    color: $main-color;
    border-bottom: 4px solid $main-color;
}
</style>