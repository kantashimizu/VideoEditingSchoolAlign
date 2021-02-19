<template lang="pug">
section.home
  //ヘッダー
  Header
  //検索エリア
  SearchBox
  div
  h2.category_title カテゴリ
  div.sliderbox
    a.slidercontent(href="/") Webアプリ開発
    a.slidercontent(href="/") スマホアプリ開発
    a.slidercontent(href="1") UX/UIデザイン
    a.slidercontent(href="1") ネットワーク・インフラ AI（人工知能）
    a.slidercontent(href="1") IoT・ロボット ゲーム（AR・VR）
    a.slidercontent(href="1") ブロックチェーン データサイエンス
    a.slidercontent(href="1") サイバーセキュリティ
  div.main
    div.main-left
      div.schol_box
        ul
          li.scholLogo
            p  1
          li.scholLogo
            p  2
          li.scholLogo
            p  3
          li.scholLogo
            p  4
          li.scholLogo
            p  5
    div.main-right
    p 受講場所
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
import Header from '@/components/Header'
import SearchBox from '@/components/SearchBox'

export default {
  name: 'index',
  components: {
    Header,
    SearchBox
  }
}
</script>
<style lang="sass">
body
  padding: 0
  margin: 0
p
  margin: 0
.category_title
  margin: 10px 0px 0px 20px
a
  text-decoration: none
.vs__search, .vs__search:focus
  display: none
.vs__clear
  display: none
.sliderbox
  display: flex
  overflow: scroll
  white-space: nowrap
  margin: 5px 0px 20px 0px
.sliderbox::-webkit-scrollbar
  display: none
.slidercontent
  margin-left: 20px
  width: 100%
.main
  background-color: red
  height: 50vh
</style>


<style lang="sass" scoped>
.home
  padding: 0
  margin: 0
  background: #ffffff
  w: hidden
</style>
