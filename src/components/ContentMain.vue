<template>
    <div id="content" class="d-flex align-items-center">
        <div class="container-lg">
            <h2 class="text-light">
                -->Content goes here &lt;--
            </h2>
        </div>

    </div>

</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

#content {
    background-color: $secondary-color;
    height: 150px;

    h2 {
        font-weight: 600;
    }
}
</style>