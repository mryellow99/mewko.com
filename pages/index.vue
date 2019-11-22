<template>
  <article class="container">
    <section class="top-image-contents">
      <img class="top-image" src="~/assets/top.png" alt="トップ画像" />
      <h1>NEKONOTEYA<br />YOSHIMURA MEIKO<br />WEB SITE</h1>
    </section>

    <Profile />

    <section class="top-image-contents">
      <img class="top-image" src="~/assets/top.png" alt="トップ画像" />
    </section>

    <section class="top-works text-center">
      <h2 class="top-section-titile">WORKS</h2>
      <section class="flex-box">
        <section>
          <img src="" alt="サムネイル画像1" />
          <h3>作品タイトル</h3>
          <p>カテゴリ</p>
        </section>

        <section>
          <img src="" alt="サムネイル画像1" />
          <h3>作品タイトル</h3>
          <p>カテゴリ</p>
        </section>
      </section>
    </section>

    <section class="top-image-contents text-center">
      <img class="top-image" src="~/assets/top.png" alt="トップ画像" />
    </section>

    <Contact />
  </article>
</template>

<script>
import Profile from '~/components/top/Profile.vue'
import Contact from '~/components/top/Contact.vue'

export default {
  components: {
    Profile,
    Contact
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
}

.top-image {
  text-align: center;
  width: 100%;
  height: 600px;
  object-fit: cover;
  object-position: left -150px;
}

.top-image-contents {
  position: relative;
}

.top-image-contents h1 {
  font-size: 4em;
  position: absolute;
  top: 45%;
  left: 3%;
  color: #f3f3f3;
}

.top-more-link {
  text-decoration: none;
  padding: 1em;
  display: inline-block;
  border-radius: 30px;
  border: 1px solid;
  width: 30%;
  margin-bottom: 88px;
}

@media screen and (max-width: 640px) {
  .top-image-contents h1 {
    font-size: 1.5em;
  }
  .top-image {
    width: 100vw;
    height: 146vw;
    object-fit: cover;
  }
}
</style>
