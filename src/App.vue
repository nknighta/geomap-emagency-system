<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    障がい者向け救援システム(仮)
    <div class="wrapper">
      <nav>
        <RouterLink to="/">ホーム</RouterLink>
        <RouterLink to="/about">設定</RouterLink>
      </nav>
    </div>
  </header>
  <RouterView />
  (c) cid buisiness project
</template>

<style scoped>

</style>