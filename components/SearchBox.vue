<template lang="pug">
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
</template>

<script>
export default {
  name: 'SearchBox',
  data() {
    return {
      selected: '',
      prefecture: {},
      price: ['無料','5万円未満','5万円〜10万円','10万円〜20万円','20万円〜50万円','50万円以上']
    }
  }

}
</script>

<style lang="sass" scoped>
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
</style>
