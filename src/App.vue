<script>
import NavHeader from './components/NavHeader.vue';
import JumbotronComponent from './components/JumbotronComponent.vue';
import ContentMain from './components/ContentMain.vue';
import MerchandiseMain from './components/MerchandiseMain.vue';
import ListLinkFooter from './components/ListLinkFooter.vue';
import SocialFooter from './components/SocialFooter.vue';
import EndFooter from './components/EndFooter.vue';


export default {
  components: {
    NavHeader,
    JumbotronComponent,
    ContentMain,
    MerchandiseMain,
    ListLinkFooter,
    SocialFooter,
    EndFooter
  }
}
</script>

<template>
  <NavHeader />

  <main>
    <JumbotronComponent />
    <ContentMain />
    <MerchandiseMain />
  </main>

  <footer>
    <ListLinkFooter />
    <SocialFooter />
    <EndFooter />
  </footer>

</template>

<style lang="scss">
@use './styles/general.scss' as *;
@use './styles/partials/variables' as *;
@use 'bootstrap/scss/bootstrap.scss' as *;
</style>
