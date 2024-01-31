<template>
  <div class="back-black">
    <div class="main">
      <div class="container">
        <h1 class="text">--> Content goes here <--</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style>
.container {
  display: flex;
  flex-direction: column;
  align-items: left;
  justify-content: center;
  height: 20vh;
}
.back-black {
  background-color: black;
  width: 100vw;
  height: 20%;
}

.text {
  color: white;
}
</style>
