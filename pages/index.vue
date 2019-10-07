<template>
  <section class="container">
    <img class="top-image" src="~/assets/top.png" alt="トップ画像" />
    <br />
    <section class="top-contents">
      <h1>Mewko's Portfolio</h1>
      <Menu />
    </section>
  </section>
</template>

<script>
import Menu from '~/components/Menu.vue'

export default {
  components: {
    Menu
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  color: white;
  /*width: 100%;
  /*height: 100%;*/
}

.top-image {
  text-align: center;
  width: 100%;
  object-fit: contain;
}

.top-contents {
  position: fixed;
  top: 50%;
  left: 5%;
}

.top-contents h1 {
  font-size: 2.5em;
}

@media screen and (max-width: 640px) {
  .top-contents h1 {
    font-size: 1.5em;
  }
  .top-image {
    width: 100vw;
    height: 146vw;
    object-fit: cover;
  }
}

.top-contents a {
  color: #eee;
  letter-spacing: 3px;
}
</style>
