<template>
  <div id="app">
    首页
    <button @click="toLogin">去登录页</button>
  </div>
</template>

<script>
import modal from '../../components/modal.vue'
export default {
  components: {
    modal
  },
  data() {
    return {
      msg: 'Use Vue 2.0 Today!'
    }
  },
  methods: {
    gogogo() {
      location.assign('../customer/home.html')
    },
    toLogin() {
      location.assign('../user/login.html')
    }
  }
}
</script>

<style lang="postcss">
.index-card {
  width: 800px;
  margin: 100px auto;
}
</style>
