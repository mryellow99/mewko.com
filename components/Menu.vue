<template>
  <nav class="nav-menu">
    <a href="/profile">top</a>
    <a href="/profile">profile</a>
    <a href="/wants">wants</a>
    <a href="/works">works</a>
    <a href="/">contact</a>
  </nav>
</template>

<style scoped>
.nav-menu {
  background: #222;
  padding: 0 16px;
}
.nav-menu a {
  text-decoration: none;
  color: #fff;
  display: inline-block;
  margin: 16px 30px;
  padding: 2px;
  font-weight: bold;
  border-bottom: 1px dotted;
  border-color: #222;
}
.nav-menu a:hover {
  border-color: #fff;
}
</style>
