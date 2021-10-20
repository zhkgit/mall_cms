<template>
  <div class="app">
    <router-link to="/main">home</router-link> |
    <router-link to="/login">登陆</router-link>
  </div>
  <router-view />
</template>

<script type="ts">
import { defineComponent } from '@vue/composition-api'
export default defineComponent({
  components: {},
  name: "App"

})
</script>

<style lang="less"></style>
