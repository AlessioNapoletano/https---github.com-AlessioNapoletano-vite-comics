<script>
import NavHeader from './components/NavHeader.vue';
import ContentMain from './components/ContentMain.vue';
import MerchandiseMain from './components/MerchandiseMain.vue';
import ListLinkFooter from './components/ListLinkFooter.vue';
import SocialFooter from './components/SocialFooter.vue'


export default {
  components: {
    NavHeader,
    ContentMain,
    MerchandiseMain,
    ListLinkFooter,
    SocialFooter,
  }
}
</script>

<template>
  <NavHeader />

  <main>
    <ContentMain />
    <MerchandiseMain />
  </main>

  <footer>
    <ListLinkFooter />
    <SocialFooter />
  </footer>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
