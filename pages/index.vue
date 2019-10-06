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
}

.top-image {
  text-align: center;
}

.top-contents {
  position: fixed;
  top: 50%;
  left: 5%;
}

.top-contents h1 {
  font-size: 2.5em;
}

.top-contents a {
  color: #eee;
  letter-spacing: 3px;
}
</style>
