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
      img(src="https://placehold.jp/350x60.png")
      ul.links
        li HOME
        li ランキング
        li カテゴリ
        li スクール検索
        li 口コミを書く
  div.search
    div.search_home
      div.search_home-input
        h2 検索
        input(
          placeholder="検索"
          name="search_text"
          type="text"
        )
      div.search_home-selects
        div.select
          p 受講場所
          v-select.input(
            v-model="selected"
            placeholder="価格を選択"
            :options="price"
          )
        div.select
          p 価格
          v-select.input(
            v-model="selected"
            placeholder="価格を選択"
            :options="price"
          )
        div.select
          p 口コミ
          v-select.input(
            v-model="selected"
            placeholder="価格を選択"
            :options="price"
          )
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
export default {
  name: 'index',
  data() {
    return {
      selected: '',
      prefecture: {},
      price: ['無料','5万円未満','5万円〜10万円','10万円〜20万円','20万円〜50万円','50万円以上']
    }
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
  .header
    .header_top
      height: 60px
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
      img
        width: auto
      .links
        color: #ffffff
        display: flex
        list-style: none
        width: auto
        li
          margin-left: 22px
.search
  background: red
  padding: 10px 0
  .search_home
    max-width: 900px
    background: #ffffff
    border-radius: 5px
    margin: 0 auto
    padding: 30px 5% 15px 5%
    &-input
      h2
        font-size: 20px
        color: #1a3153
      input
        width: 100%
        padding: 0 0 0 8px
        color: #1a3153
        height: 36px
        border: 1px solid #dddddd
        border-radius: 2px
    &-selects
      display: flex
      color: #1a3153
      .select
        margin-top: 18px
        width: 33%
        p
          font-size: 16px
          font-weight: bold
        .input
          border: 1px solid #1a3153
          border-radius: 5px
          width: 70%
          span
            white-space: nowrap
            font-size: 12px
        #vs1__combobox
          border: none
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
