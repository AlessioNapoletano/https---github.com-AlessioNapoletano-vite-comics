<script>
export default {
    data() {
        return {
            navList:
                [
                    {
                        text: "CHARACTERS"
                    },
                    {
                        text: "COMICS"
                    },
                    {
                        text: "MOVIES"
                    },
                    {
                        text: "TV"
                    },
                    {
                        text: "GAMES"
                    },
                    {
                        text: "COLLECTIBLES"
                    },
                    {
                        text: "VIDEOS"
                    },
                    {
                        text: "FANS"
                    },
                    {
                        text: "NEWS"
                    },
                    {
                        text: "SHOP"
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
                    <li v-for="item in navList">
                        {{ item.text }}
                    </li>
                </ul>
            </nav>
        </div>

    </header>
</template>

<style lang="scss">
header {
    border: 1px solid black;
}

ul {
    display: flex;

    li {
        list-style-type: none;
        padding: 1rem;
        font-weight: bold;
    }
}
</style>