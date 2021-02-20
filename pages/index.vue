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
      div.content-table
        div.main-box
          h1.category-1 人 気
          ul#slideshow
            li.showSlide
              img(src="https://placehold.jp/50x50.png")
            li.showSlide
              img(src="0.png")
            li.showSlide
              img(src="https://placehold.jp/50x50.png")
        div.aside-box
          p aaa
    div.main-right
  // footer
  div.sliderbox
    a.slidercontent(href="/") Webアプリ開発
    a.slidercontent(href="/") スマホアプリ開発
    a.slidercontent(href="1") UX/UIデザイン
    a.slidercontent(href="1") ネットワーク・インフラ AI（人工知能）
    a.slidercontent(href="1") IoT・ロボット ゲーム（AR・VR）
    a.slidercontent(href="1") ブロックチェーン データサイエンス
    a.slidercontent(href="1") サイバーセキュリティ
  div#contact-content
    div.contact
      div.contact-table
        div.contact-box
          p.pt10 [ 当サイトに関するお問い合わせフォーム ]
          form(action='' method='')
            p.font-5.text-red.mt10 ※下記内容を入力の上、送信ボタンをクリックしてください。
            div.contact-contents
              div#contact-name
                label(for='mail') メールアドレス：
                input(type='email' name='email')
              div#contact-name
                label(for='name') お名前：
                input(type='text' name='name')
              div#contact-name
                label(for='name') ふりがな：
                input(type='text' name='name')
              div#contact-name
                label(for='name') お問い合わせ項目：
                select(name="item")
                  option(value='service') サービスについて
                  option(value='page') ページについて
                  option(value='other') その他
              div#contact-name
                label(for='name') 内容：
                textarea(row='20' cols='50' type='text' name='name')
              div#contact-name
                input.text-right(type='submit' value='送信')
  footer.footer-top
    //- div
    //-   ul.footer-sns
    //-     li.sns-links
    //-       a(href="/")
    //-         img(src="https://placehold.jp/50x50.png")
    //-     li.sns-links
    //-       a(href="/")
    //-         img(src="https://placehold.jp/50x50.png")
    //-     li.sns-links
    //-        a(href="/") coming soon
    //-     li.sns-links
    //-        a(href="/") coming soon
    //-     li.sns-links
    //-        a(href="/") coming soon
  footer.footer-bottom
    p.footer-text.right プログラミングスクール 口コミ・評判サイト VideoEdithingSchoolAlign
    p.footer-text.left © 2021 VideoEdithingSchoolAlign
    script

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
.contact-contents
#main-contents
  background-color: red
  height: 100vh
  display: flex
.main-left
  width: 70%
  height: 100vh
  background-color: rgba 0 0 0 0
.content-table
  width: 100%
.main-box
  height: 50vh
  background-color: #fff
  margin: 35px 30px 50px 30px
  border-radius: 2px
  .category-1
    position: relative
    padding: 0.5rem 1.2rem
    border: 2px solid #000
    border-radius: 10px
    background-color: #fff
  #slideshow
    display: flex
    position: relative
    margin: 0 auto
    height: 40vw
    display: flex
    justify-content: center
    opacity: 0
    animation: mainFadeIn 2s ease forwards 1.8s
  .showslide
    position: relative
    width: 100vw
    overflow: hidden
.aside-box
  height: 30vh
  background-color: #fff
  margin: 17px 30px 25px 30px
  border-radius: 2px
.main-right
  width: 30%
  height: 100vh
  background-color: rgba 0 0 0 0
  border: solid 1px #000
#contact-content
  background-color: red
  padding-top: 35px
  padding-bottom: 40px
.contact
  width: 100%
  text-align: center
  .contact-box
    background-color: #fff
    border-radius: 5px
  .contact-table
    width: 50%
    margin: 10px auto
  .font-5
    font-size: 5px
  .text-red
    color: red
  .mt10
    margin-top: 10px
  .pt10
    padding-top: 10px
input
#contact-name
  border-radius: 3px
  padding: 5px 110px 15px 5px
  text-align: right
  .text-right
    text-align: right
select
  padding-left: 24px
  value
  text-align: right
textarea
  resize: none
  max-width: 50%;
  height: 80px
  border-radius: 2px;
  padding: 5px 5px 5px 5px
  border: 1px solid black;
.footer-top
  height: 80px
  background: #1c385e
  opacity: 0.9
  display: flex
  align-items: center
  justify-content: space-between
  padding: 0 50px
  font-size: 24px
  .footer-sns
    display: flex
    text-align: center
    list-style: none
    margin-left: 20px
  .sns-links
    text-decoration: none
    padding-left: 95px
.footer-bottom
  height: 60px
  padding: 0 50px
  background: #1c385e
  display: flex
  justify-content: space-between
  align-items: center
  .footer-text
    color: #ffffff
.left
  text-align: left
.right
  text-align: right
</style>


<style lang="sass" scoped>
.home
  padding: 0
  margin: 0
  background: #ffffff
  w: hidden
</style>
