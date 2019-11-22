<template>
  <article class="container">
    <section class="top-image-contents">
      <img class="top-image" src="~/assets/top.png" alt="トップ画像" />
      <h1>NEKONOTEYA<br />YOSHIMURA MEIKO<br />WEB SITE</h1>
      <Menu />
    </section>

    <section class="top-profile text-center top-section-max-width">
      <h2 class="top-section-titile">PROFILE</h2>
      <section class="flex-box margin-bottom-64">
        <img
          class="profile-icon-image"
          src="~/assets/icon.png"
          alt="よしむらめいこアイコン画像"
        />

        <section class="text-left">
          <h3>よしむらめいこ</h3>
          <h4>WEBデザイナー, プログラマ, イラストレーター</h4>
          <p>
            仙台在住、二児の母。デザイナー歴、プログラマ歴ともに5年目。座右の銘は「なんでもできる！なんでもなれる！輝く未来を抱きしめて！」
          </p>
          <br />
          <h4>SKILL , FRAMEWORK</h4>
          <p>
            HTML / CSS / PHP / Javascript / Nuxt.js / Vue.js / WordPressAdobe
            Illustrator / Adobe Photoshop / Adobe XD / CLIP STUDIO PAINT
          </p>
        </section>
      </section>
      <a class="top-more-link margin-bottom-64" href="/">もっと見る</a>
    </section>

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

    <section>
      <h2 class="top-section-titile">CONTACT</h2>
      <p>
        お仕事のご依頼やご相談などありましたら、ぜひお気軽にご連絡ください。お待ちしています♪
      </p>
      <p>お問い合わせフォームが入る</p>
    </section>
  </article>
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
  /* color: white; */
  /*width: 100%;
  /*height: 100%;*/
}

.top-image {
  text-align: center;
  width: 100%;
  height: 650px;
  object-fit: cover;
  /* object-position: left center; */
  object-position: left -180px;
}

.top-image-contents {
  position: relative;
}

.top-image-contents h1 {
  font-size: 5em;
  position: absolute;
  top: 50%;
  left: 3%;
  color: #fcfcfc;
}

.profile-icon-image {
  border-radius: 50%;
  width: 180px;
  margin-right: 42px;
}

.top-section-titile {
  font-size: 3em;
  margin: 72px 0;
}

.top-section-max-width {
  max-width: 720px;
  margin: 0 auto;
}

.top-more-link {
  text-decoration: none;
  padding: 1em;
  display: inline-block;
  border-radius: 30px;
  border: 1px solid;
  width: 30%;
  margin-bottom: 64px;
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

.top-image-contents a {
  color: #eee;
  letter-spacing: 3px;
}
</style>
