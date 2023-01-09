<script>
export default {

}
</script>

<template>
    <div id="follow-us">
        <div class="container-lg">
            <div class="d-flex justify-content-between py-5">

                <div class="button">
                    <a href="#" class="btn btn-primary">SIGN UP NOW</a>
                </div>

                <div class="social d-flex">
                    <h3 class="me-5">
                        FOLLOW US
                    </h3>

                    <div class="social-icon d-flex">
                        <div class="image-fluid">
                            <img src="../assets/img/footer-facebook.png" alt="Logo Facebook">
                        </div>
                        <div class="image-fluid">
                            <img src="../assets/img/footer-periscope.png" alt="Logo Periscope">
                        </div>
                        <div class="image-fluid">
                            <img src="../assets/img/footer-pinterest.png" alt="Logo Pinterest">
                        </div>
                        <div class="image-fluid">
                            <img src="../assets/img/footer-twitter.png" alt="Logo Twitter">
                        </div>
                        <div class="image-fluid">
                            <img src="../assets/img/footer-youtube.png" alt="Logo Youtube">
                        </div>
                    </div>
                </div>

            </div>
        </div>



    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

#follow-us {
    background-color: #333333;
}

h3 {
    color: $main-color;
    font-weight: 600;
}

img {
    margin-right: 1rem;
}
</style>