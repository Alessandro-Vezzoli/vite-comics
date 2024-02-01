<template>
  <div class="back-blue">
    <div class="main">
      <div class="container">
        <div class="image-container">
          <div class="icon-list">
            <div class="icon-item">
              <div class="content-wrapper">
                <div class="image-wrapper">
                  <img
                    src="/img/buy-comics-digital-comics.png"
                    alt="Icon buy-comics-digital-comics"
                    class="image"
                  />
                </div>

                <div class="caption">
                  <p>DIGITAL COMICS</p>
                </div>
              </div>
            </div>
            <div class="icon-item">
              <div class="content-wrapper">
                <div class="image-wrapper">
                  <img
                    src="/img/buy-comics-merchandise.png"
                    alt="Icon buy-comics-merchandise"
                    class="image"
                  />
                </div>

                <div class="caption">
                  <p>DC MERCHANDISE</p>
                </div>
              </div>
            </div>
            <div class="icon-item">
              <div class="content-wrapper">
                <div class="image-wrapper">
                  <img
                    src="/img/buy-comics-subscriptions.png"
                    alt="Icon buy-comics-subscriptions"
                    class="image"
                  />
                </div>

                <div class="caption">
                  <p>SUBSCRIPTION</p>
                </div>
              </div>
            </div>
            <div class="icon-item">
              <div class="content-wrapper">
                <div class="image-wrapper">
                  <img
                    src="/img/buy-comics-shop-locator.png"
                    alt="Icon buy-comics-shop-locator"
                    class="image"
                  />
                </div>

                <div class="caption">
                  <p>COMIC SHOP LOCATOR</p>
                </div>
              </div>
            </div>
            <div class="icon-item">
              <div class="content-wrapper">
                <div class="image-wrapper">
                  <img
                    src="/img/buy-dc-power-visa.svg"
                    alt="Icon buy-dc-power-visa"
                    class="image-svg image"
                  />
                </div>

                <div class="caption">
                  <p>DC POWER VISA</p>
                </div>
              </div>
            </div>

            <!-- Ripeti per gli altri elementi -->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AppPreFooter",
};
</script>
<style scoped>
.container {
  display: flex;
  align-items: left;
  justify-content: center;
}

.back-blue {
  background-color: rgb(0, 162, 255);
  width: 100vw;
  height: 20vh;
}

.icon-list {
  display: flex;
  justify-content: space-around;
}

.icon-item {
  width: 22%;
  margin-bottom: 20px;
}

.content-wrapper {
  display: flex;
  align-items: center;
}

.image-wrapper {
  margin-bottom: 10px;
}

.image {
  max-width: 50px;
  max-height: 50px;
  padding: 10px;
}

.image-svg {
  width: 50px;
  height: 60px;
  padding-left: 50px;
}
.caption {
  text-align: left;
  color: white;
  width: 100%;
  padding-left: 10px;
}
</style>
