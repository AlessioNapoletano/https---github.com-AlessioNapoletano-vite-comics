<script>
import NavHeader from './components/NavHeader.vue';
import ContentMain from './components/ContentMain.vue';
import MerchandiseMain from './components/MerchandiseMain.vue';


export default {
  components: {
    NavHeader,
    ContentMain,
    MerchandiseMain,
  }
}
</script>

<template>
  <NavHeader />

  <main>
    <ContentMain />
    <MerchandiseMain />
  </main>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
