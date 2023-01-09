<script>
import NavHeader from './components/NavHeader.vue';
import ContentMain from './components/ContentMain.vue';


export default {
  components: {
    NavHeader,
    ContentMain,
  }
}
</script>

<template>
  <NavHeader />

  <main>
    <ContentMain />
  </main>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
