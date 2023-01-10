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
    <div class="magazine">
        <img :src="thumb">
        <h2> {{ price }} - {{ series }} -- {{ type }}</h2>
    </div>
</template>

<style lang="scss" scoped>

</style>