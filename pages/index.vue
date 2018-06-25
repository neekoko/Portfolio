<template>
  <section class="hero">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">
          Profile
        </h1>
        <p>新卒でSIerへ入社。保険や銀行系のシステム開発を経験し、レガシーな開発ではなくモダンなWeb開発がしたくて</p>
        <p>転職して1年が経ちました。最近はVue.js、Nuxt.jsにハマっています。</p>
        <p>あとDockerも使ってみたくなったので触ってます。デザインにも興味あります(*'▽'*)
        </p>
        <p>散歩が好きです。よく歩きます。疲れたら喫茶店に立ち寄りコーヒで一息つくのが大好きです。</p>
        <ul class="content-list">
          <li><i class="fab fa-github fa-lg"></i><a href="https://github.com/neekoko">neekoko</a></li>
          <li><i class="fab fa-twitter-square fa-lg"></i><a href="https://twitter.com/_neekoko">@_neekoko</a></li>
          <li><i class="fab fa-blogger fa-lg"></i><a href="http://www.topazperidot.com/">_neekoko's Blog</a></li>
        </ul>
      </div>
    </div>
    <div class="hero-body">
      <div class="container">
        <h1 class="title">
          This Site
        </h1>
        <p>初めて作ったポートフォリオです。勉強中のNuxtを使って作ってみました。</p>
        <p>Qiitaにこのサイトの記事を投稿していますのでそちらもご覧頂けると幸いです。</p>
        <p>
          <a href="https://qiita.com/_neekoko/items/aaedba104bb4997ab976">
            Nuxt+Netlifyでサイトを公開してみた！
          </a>
        </p>
        <ul>
          <li class="float-left"><figure class="image is-64x64"><img src="~/assets/vue.svg"></figure></li>
          <li class="float-left icon-plus"><i class="fas fa-plus"></i></li>
          <li class="float-left"><figure class="image is-64x64"><img src="~/assets/nuxt.svg"></figure></li>
          <li class="float-left icon-plus"><i class="fas fa-plus"></i></li>
          <li class="float-left"><figure class="image is-64x64"><img src="~/assets/netlify.svg"></figure></li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>

</script>

<style>
  ul {
    margin-top: 20px;
  }

  li {
    margin-bottom: 10px;
  }

  i {
    margin-right: 3px;
  }

  .float-left {
    float: left;
  }

  .icon-plus {
    margin-left: 5px;
    margin-right: 5px;
  }
</style>
