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
  div.contact
    div.contact-table
      p 当サイトに関するお問い合わせフォームです。
      form(action="" method="")
        p.font-5.text-red ※下記内容入力の上、「確認画面へ」ボタンをクリックしてください。
        div#contact-name
          label(for='name') お名前：
          input(type='text' name='name')
        div#contact-name
          label(for='name') お問い合わせ内容：
          select(name="item")
            option(value='service') サービスについて
            option(value='other') その他
        div#contact-name
          label(for='mail') メールアドレス：
          input(type='email' name='email')
        div#contact-name
          input.text-right(type='submit' value='送信')


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
.main-left
  width: 70%
  height: 100vh
  background-color: rgba
  border: solid 1px #000
.main-right
  width: 30%
  height: 100vh
  background-color: rgba 0 0 0 0
  border: solid 1px #000
.contact
  width: 100%
  text-align: center
  .contact-table
    border-radius: 5px solid #000
    width: 50%
    margin: 10px auto
  .font-5
    font-size: 5px
  .text-red
    color: red
input
#contact-name
  order-radius: 3px
  padding: 5px 20px
  text-align: left
  .text-right
    text-align: right
</style>


<style lang="sass" scoped>
.home
  padding: 0
  margin: 0
  background: #ffffff
  w: hidden
</style>
