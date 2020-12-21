<template lang="pug">
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
</template>

<script>
export default {
  name: 'header'
}
</script>

<style lang="sass" scoped>
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
</style>
