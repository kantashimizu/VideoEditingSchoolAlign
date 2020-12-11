<template lang="pug">
section.home
  div.header
    div.header_top
      div.header_top-text
        p VideoEdithingSchoolAlign
      div.header_top-right
        p.btn_left 口コミを書く
        p.btn_right お問い合わせ
    div.header_bottom
      div: img(src="https://placehold.jp/350x60.png")
      ul.links
        li HOME
        li ランキング
        li カテゴリ
        li スクール検索
        li  口コミを書く
    ul
      li HOME
      li ランキング
      li カテゴリ
    ul
      li アイテム
      li HOME
      li ランキング
      li カテゴリ
      li HOME
      li ランキング
      li カテゴリ
      li HOME
      li ランキング
      li カテゴリ
      li カテゴリ
    ul

    ul
      li カテゴリ
      li HOME
      li ランキング
      li カテゴリ
      li カテゴリ
    ul
      li  口コミを書く
    p MENU
  h2 検索

  h2 カテゴリ

  h2 受講場所

  h2 価格

  h2 口コミ

  h2 詳細条件
    ul
      li オンライン
      li 無料体験
      li 就職サポート

    ul
      li トップページ
  h2 おすすめランキング

    div もっとランキングを見る

    div
  h2 カテゴリ
  div
    a(href="/") Webアプリ開発
    a(href="/") スマホアプリ開発
    a(href="1") UX/UIデザイン
    a(href="1") ネットワーク・インフラ AI（人工知能）
    a(href="1") IoT・ロボット ゲーム（AR・VR）
    a(href="1") ブロックチェーン データサイエンス
    a(href="1") サイバーセキュリティ
  h2 受講場所
    ul
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
      li (地域名)
  h2 オンラインスクール
    p 画像挿入
  h2 RANKING
  h2 ランキング
    ul
      li: a(href="/") １
      li: a(href="/") ２
      li: a(href="/") ３
      li: a(href="/") ４
      li: a(href="/") ５
  // footer
  ul
    li アイテム
    li HOME
    li ランキング
    li カテゴリ
    li HOME
  ul
    li アイテム
    li HOME
    li ランキング
  h2 お問い合わせ
  p 当サイトに関するお問い合わせフォームです。<br>
    | &emsp;お問い合わせフォーム
  p VideoEdithingSchoolAlign
  p プログラミングスクール口コミ・評判サイト VideoEdithingSchoolAlign
  ul
    li: a(href="/") SNS
    li: a(href="/") SNS
    li: a(href="/") SNS
    li: a(href="/") SNS
    li: a(href="/") SNS
  p © 2020 VideoEdithingSchoolAlign
</template>

<script>
export default {}
</script>
<style lang="sass">
body
  padding: 0
  margin: 0
</style>


<style lang="sass" scoped>
.home
  padding: 0
  margin: 0
  .header
    .header_top
      height: 40px
      padding: 0 50px
      background: #1c385e
      display: flex
      justify-content: space-between
      align-items: center
      &-text
        color: #ffffff
      &-right
        display: flex
        p
          font-size: 14px
          padding: 2px 3px
          margin-right: 10px
          border-radius: 3px
        .btn_left
          background: #f9cc46
        .btn_right
          color: #ffffff
          background: #df1843
    .header_bottom
      height: 80px
      background: #1c385e
      opacity: 0.9
      display: flex
      align-items: center
      justify-content: space-between
      padding: 0 50px
      font-size: 24px
      .links
        color: #ffffff
        display: flex
        list-style: none
        li
          margin-left: 15px
</style>
