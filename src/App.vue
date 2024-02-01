<template>
  <div>
    <AppHeader></AppHeader>
    <AppContent></AppContent>
    <AppPreFooter></AppPreFooter>
    <AppFooter></AppFooter>
  </div>
</template>
<script>
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppPreFooter from "./components/AppPreFooter.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  components: {
    AppHeader,
    AppContent,
    AppPreFooter,
    AppFooter,
  },
};
</script>

<style scoped></style>
