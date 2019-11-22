<template>
  <div>
    <header>
      <Menu />
    </header>
    <nuxt />
    <Footer />
  </div>
</template>

<script>
import Menu from '~/components/Menu.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    Menu,
    Footer
  }
}
</script>

<style>
/** global **/
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.text-center {
  text-align: center;
}
.text-left {
  text-align: left;
}
.flex-box {
  display: flex;
}
.margin-bottom-64 {
  margin-bottom: 64px;
}

/** top **/
.top-section-titile {
  font-size: 3em;
  margin: 72px 0;
}
.top-section-max-width {
  max-width: 720px;
  margin: 0 auto;
}
</style>
