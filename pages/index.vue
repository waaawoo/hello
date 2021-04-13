<template>
  <section>
    <!-- pagesのindex.jsを編集する -->
    <!-- Nuxt.jsはほっとりローディングする（自動で編集を反映してくれる）Dev環境のみ -->
    <p>Hello World</p>
    <p>{{message}}</p>
  </section>
</template>

<script>
export default {
  data (){
    return {
      message: "メッセージ"
    }
  }
}
</script>

<style>

</style>
