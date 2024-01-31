<template>
  <div class="main">
    <div class="menu">
      <div>
        <img class="logo" src="/img/dc-logo.png" />
      </div>
      <div>
        <ul class="menu-list">
          <li>
            <a href="#">CHARACTERS</a>
          </li>
          <li>
            <a href="#">COMICS</a>
          </li>
          <li>
            <a href="#">MOVIES</a>
          </li>
          <li>
            <a href="#">TV</a>
          </li>
          <li>
            <a href="#">GAMES</a>
          </li>
          <li>
            <a href="#">COLLECTIBLES</a>
          </li>
          <li>
            <a href="#">VIDEOS</a>
          </li>
          <li>
            <a href="#">FANS</a>
          </li>
          <li>
            <a href="#">NEWS</a>
          </li>
          <li>
            <a href="#">SHOP</a>
          </li>
        </ul>
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
.logo {
  width: 80px;
}
.menu {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 150px;
}

.menu-list {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

.menu-list li {
  display: inline-block;
  margin-right: 30px;
}

.menu-list a {
  text-decoration: none;
  color: black;
  transition: color 0.3s; /* Add a smooth transition effect */
}

.menu-list a:hover {
  color: blue; /* Change color on hover */
}
</style>
