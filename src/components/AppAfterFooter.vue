<template>
  <div class="background-black main">
    <!-- Sign up button -->
    <button class="signup-button">SIGN-UP NOW!</button>

    <!-- Follow Us images -->
    <div class="follow-us-container">
      <p class="follow-text">FOLLOW US</p>
      <img
        src="/img/footer-facebook.png"
        alt="Facebook"
        class="follow-us-image"
      />
      <img
        src="/img/footer-twitter.png"
        alt="Twitter"
        class="follow-us-image"
      />
      <img
        src="/img/footer-youtube.png"
        alt="Youtube"
        class="follow-us-image"
      />
      <img
        src="/img/footer-pinterest.png"
        alt="Pinterest"
        class="follow-us-image"
      />
      <img
        src="/img/footer-periscope.png"
        alt="Periscope"
        class="follow-us-image"
      />
    </div>
  </div>
</template>
<script>
export default {
  name: "AppAfterFooter",
};
</script>
<style scoped>
.background-black {
  background-color: black;
  height: 100px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.signup-button {
  border: 2px solid blue;
  background-color: transparent;
  color: blue;
  padding: 10px;
  margin-right: auto;
  color: white;
}

.follow-us-container {
  display: flex;
  align-items: center;
  justify-content: flex-end; /* Align images to the right */
  margin-top: 10px; /* Adjust as needed */
}

.follow-us-image {
  width: 30px; /* Adjust the width as needed */
  margin-left: 10px; /* Adjust the spacing between images */
}
.follow-text {
  color: blue;
  padding-right: 30px;
}
</style>
