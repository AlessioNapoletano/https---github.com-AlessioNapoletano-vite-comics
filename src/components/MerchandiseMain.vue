<script>
export default {
    data() {
        return {
            iconList:
                [
                    {
                        image: 'buy-comics-digital-comics.png',
                        text: 'DIGITAL COMICS'
                    },
                    {
                        image: 'buy-comics-merchandise.png',
                        text: 'DC MERCHANDISE'
                    },
                    {
                        image: 'buy-comics-subscriptions.png',
                        text: 'SUBSCRIPTION'
                    },
                    {
                        image: 'buy-comics-shop-locator.png',
                        text: 'COMIC SHOP LOCATOR'
                    },
                    {
                        image: 'buy-dc-power-visa.svg',
                        text: 'DC POWER VISA'
                    }
                ]
        }
    }
}
</script>

<template>
    <div id="merchandise" class="d-flex align-items-center text-light fw-bold">
        <div class="container-lg">
            <ul class="d-flex align-items-center justify-content-between">
                <li v-for="item in iconList">
                    <img :src="`src/assets/img/${item.image}`" :alt="'logo' + item.text">
                    <span>
                        {{ item.text }}
                    </span>
                </li>
            </ul>

        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

#merchandise {
    background-color: $main-color;
    height: 180px;
}

span {
    font-size: .8rem;
}

img {
    height: 50px;
    margin-right: .2rem;
}

li {
    list-style-type: none;
    padding: 0rem 2rem;
}
</style>