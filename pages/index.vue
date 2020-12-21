<template lang="pug">
section.home
  //ヘッダー
  Header
  //検索エリア
  SearchBox
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
h2
  margin: 0
.vs__search, .vs__search:focus
  display: none
.vs__clear
  display: none
</style>


<style lang="sass" scoped>
.home
  padding: 0
  margin: 0
  background: #ffffff
    // .search_home-centerbox
    //   align-items: center
    //   justify-content: space-between
    //   border-radius: 20px
    //   background: #ffffff
    //   height: 100%
    //   float: left
    //   width: 100%
    //   .search_home-text
    //     display: inline-block
    //     .select_box
    //       display: inline-block
    //       list-style: none
    //       margin: 23px 89px
    // .main-content
      //padding: 30px 5%
      //width: 100%
      //max-width: 100%
      //padding-bottom: 50px
      //float: none
      .main-ranking
        background: #ffffff
        //position: relative
        text-align: center
        overflow: hidden

</style>
