<template>
  <div>
    <AppHeader></AppHeader>
    <AppContent></AppContent>
    <AppPreFooter></AppPreFooter>
    <div class="background-img">
      <div class="main">
        <div class="container">
          <h1>ciao</h1>
        </div>
      </div>
    </div>
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

<style>
.container {
  display: flex;
  align-items: left;
  justify-content: center;
}
.background-img {
  background-image: url("./img/footer-bg.jpg");
  background-repeat: no-repeat;
  background-position: top;
  background-size: cover;
  height: 35vh;
}
</style>
