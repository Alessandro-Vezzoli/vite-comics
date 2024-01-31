<template>
  <div>
    <AppHeader></AppHeader>
    <AppContent></AppContent>
    <AppPreFooter></AppPreFooter>
  </div>
</template>
<script>
import AppHeader from "./components/AppHeader.vue";
import AppContent from "./components/AppContent.vue";
import AppPreFooter from "./components/AppPreFooter.vue";
export default {
  components: {
    AppHeader,
    AppContent,
    AppPreFooter,
  },
};
</script>

<style></style>
