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
  <div>
    <AppHeader></AppHeader>
    <AppMainContent />
    <AppFooter />
  </div>
</template>

<style scoped>
  /* @use './styles/generals.scss' as *; */
</style>