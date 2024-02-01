<template>
  <div class="background-img">
    <div class="main">
      <div class="lists-container">
        <div class="list-container">
          <h3>DC COMICS</h3>
          <ul class="list">
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <h3>SHOP</h3>
          <ul class="list">
            <li>Shop DC</li>
            <li>Shop DC COllectibles</li>
          </ul>
        </div>

        <div class="list-container">
          <h3>DC</h3>
          <ul class="list">
            <li>Terms Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div class="list-container">
          <h3>SITES</h3>
          <ul class="list">
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
        <img src="/img/dc-logo-bg.png" alt="logo-footer" class="logo-footer" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AppFooter",
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
  height: auto;
}
.lists-container {
  display: flex;
  padding-top: 20px;
  padding-bottom: 20px;
}

.list-container {
  flex: 1;
  color: white;
}

.list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.list li {
  color: #888;
  margin-bottom: 8px;
}
.logo-footer {
  max-height: 500px;
}
</style>
