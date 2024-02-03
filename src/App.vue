<template>
  <div>
    <AppHeader></AppHeader>
    <AppContent></AppContent>
    <AppPreFooter></AppPreFooter>
    <AppFooter></AppFooter>
    <AppAfterFooter></AppAfterFooter>
  </div>
</template>
<script>
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppPreFooter from "./components/AppPreFooter.vue";
import AppFooter from "./components/AppFooter.vue";
import AppAfterFooter from "./components/AppAfterFooter.vue";

export default {
  components: {
    AppHeader,
    AppContent,
    AppPreFooter,
    AppFooter,
    AppAfterFooter,
  },
};
</script>

<style scoped></style>
