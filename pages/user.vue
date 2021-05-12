<template>
  <div> 用户管理导航，
    <nuxt-link :to="'/user/101'">修改</nuxt-link>
    <nuxt-child/>
    <nuxt-link :to="'/user/one'">one页面</nuxt-link>
  </div>
</template>
<script>
  export default {
    layout: "test"
  }
</script>
<style></style>
