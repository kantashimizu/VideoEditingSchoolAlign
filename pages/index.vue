<template lang="pug">
section.home
  //ヘッダー
  Header
  //検索エリア
  SearchBox
  div
  div.sliderbox
    a.slidercontent(href="/") Webアプリ開発
    a.slidercontent(href="/") スマホアプリ開発
    a.slidercontent(href="1") UX/UIデザイン
    a.slidercontent(href="1") ネットワーク・インフラ AI（人工知能）
    a.slidercontent(href="1") IoT・ロボット ゲーム（AR・VR）
    a.slidercontent(href="1") ブロックチェーン データサイエンス
    a.slidercontent(href="1") サイバーセキュリティ
  div#main-contents
    div.main-left
    div.main-right
  // footer
  div.sliderbox
    a.slidercontent(href="/") ０００００
    a.slidercontent(href="/") １１１１１
    a.slidercontent(href="1") ２２２２２
    a.slidercontent(href="1") ３３３３３
    a.slidercontent(href="1") ４４４４４
    a.slidercontent(href="1") ５５５５５
    a.slidercontent(href="1") ６６６６６
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
a:link,a:visited,a:hover,a:active
  color: #000
.vs__search, .vs__search:focus
  display: none
.vs__clear
  display: none
.sliderbox
  display: flex
  overflow: scroll
  white-space: nowrap
  margin: 15px 30px 15px 0px
  z-line: 1
.sliderbox::-webkit-scrollbar
  display: none
.slidercontent
  margin-left: 20px
  width: 100%
#main-contents
  background-color: red
  height: 100vh
  display: flex
  flex: column
.main-left
  width: 70%
  height: 100vh
  background-color: rgba
  border: solid 1px #000
// .main
//   width: 90%
//   height: 100vh
// .main-01
//   width: 70%
//   height: 150px
//   margin: 0 auto
//   background-color: white
//   position: relative
//   border-radius: 5px
.main-right
  width: 30%
  height: 100vh
  background-color: rgba 0 0 0 0
  border: solid 1px #000
</style>


<style lang="sass" scoped>
.home
  padding: 0
  margin: 0
  background: #ffffff
  w: hidden
</style>
