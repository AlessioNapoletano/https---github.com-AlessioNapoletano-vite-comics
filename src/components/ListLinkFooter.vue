<script>
export default {
    data() {
        return {
            dcComicsList:
                [
                    {
                        text: 'Characters',
                    },
                    {
                        text: 'Comics',
                    },
                    {
                        text: 'Movies',
                    },
                    {
                        text: 'TV',
                    },
                    {
                        text: 'Games',
                    },
                    {
                        text: 'Videos',
                    },
                    {
                        text: 'News',
                    }
                ],
            shopList:
                [
                    {
                        text: 'Shop DC',
                    },
                    {
                        text: 'Shop DC Collectibles',
                    }
                ],
            dcList:
                [
                    {
                        text: 'Terms Of Use',
                    },
                    {
                        text: 'Privacy policy (New)',
                    },
                    {
                        text: 'Ad Choices',
                    },
                    {
                        text: 'Advertising',
                    },
                    {
                        text: 'Jobs',
                    },
                    {
                        text: 'Subscriptions',
                    },
                    {
                        text: 'Talent Workshops',
                    },
                    {
                        text: 'CPSC Certofocates',
                    },
                    {
                        text: 'Ratings',
                    },
                    {
                        text: 'Shop Help',
                    },
                    {
                        text: 'Contact Us',
                    },
                ],
            sitesList:
                [
                    {
                        text: 'DC',
                    },
                    {
                        text: 'MAD Magazine',
                    },
                    {
                        text: 'DC Kids',
                    },
                    {
                        text: 'DC Universe',
                    },
                    {
                        text: 'DC Power Visa',
                    }
                ]
        }
    }

}
</script>

<template>
    <div id="footer-link">
        <div class="container-lg">
            <div class="row">
                <!--col for link-->
                <div class="col-6">
                    <div class="row">
                        <div class="col-4">
                            <!--DC Comics Link-->
                            <nav class="pt-4">
                                <h4 class="mb-3">
                                    DC COMICS
                                </h4>

                                <ul>
                                    <li v-for="item in dcComicsList">
                                        <a href="#">
                                            {{ item.text }}
                                        </a>
                                    </li>
                                </ul>
                            </nav>

                            <!--Shop Link-->
                            <nav>
                                <h4>
                                    SHOP
                                </h4>

                                <ul>
                                    <li v-for="item in shopList">
                                        <a href="#">
                                            {{ item.text }}
                                        </a>
                                    </li>
                                </ul>
                            </nav>
                        </div>

                        <div class="col-4">
                            <nav class="pt-4">
                                <h4 class="mb-3">
                                    DC
                                </h4>

                                <ul>
                                    <li v-for="item in dcList">
                                        <a href="#">
                                            {{ item.text }}
                                        </a>
                                    </li>
                                </ul>
                            </nav>

                        </div>

                        <div class="col-4">
                            <nav class="pt-4">
                                <h4 class="mb-3">
                                    SITES
                                </h4>

                                <ul>
                                    <li v-for="item in sitesList">
                                        <a href="#">
                                            {{ item.text }}
                                        </a>
                                    </li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>

                <!--Col for img-->
                <div class="col-6">
                    <div class="image-fluid">
                        <img src="../assets/img/dc-logo-bg.png" alt="DC logo">
                    </div>
                </div>
            </div>
        </div>

    </div>

</template>

<style lang="scss" scoped>
#footer-link {
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    height: 400px;
    overflow: hidden;
}


nav {
    color: white;

    h4 {
        font-weight: 600;
    }

    ul {
        padding-left: 0;
    }

    a {
        text-decoration: none;
        color: grey;
    }

}
</style>