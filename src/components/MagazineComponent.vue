<script>
export default {
    props: {
        thumb: String,
        price: Number,
        series: String,
        type: String
    }

}
</script>

<template>
    <section class="magazine">
        <img :src="thumb">
        <p class="text-light fw-bold"> {{ series.toUpperCase() }}</p>
    </section>
</template>

<style lang="scss" scoped>
.magazine {
    width: calc(100% / 6);
    padding: .5rem;
    margin-bottom: 1rem;
}
</style>