<script>
import NavHeader from './components/NavHeader.vue';

export default {
  components: {
    NavHeader,
  }
}
</script>

<template>
  <NavHeader />
</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
