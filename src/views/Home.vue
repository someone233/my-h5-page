<template>
  <div class="home">
    <page-header title="主页" noBack="true"></page-header>
    <div class="list">
      <router-link class="item" to="/ViciousSyndicate">ViciousSyndicate狂野战报</router-link>
      <router-link class="item" to="/TempoStorm">TempoStorm狂野战报</router-link>
    </div>
  </div>
</template>

<script>
  import PageHeader from '../components/PageHeader.vue'

  export default {
    name: 'Home',
    components: {
      PageHeader
    },
    data() {
      return {}
    }
  }
</script>

<style lang="less" rel="stylesheet/less" scoped>
</style>
