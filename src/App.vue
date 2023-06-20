<script>
import AppHeader from './components/AppHeader.vue';
import AppMainContent from './components/AppMainContent.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMainContent,
    AppFooter,
  }
}
</script>

<template >
  <div class="main-container">
    <AppHeader></AppHeader>
    <AppMainContent />
    <AppFooter />
  </div>
</template>

<style scoped lang="scss">
  @use './styles/generals.scss' as *;
</style>