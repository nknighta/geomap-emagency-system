<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
  </header>
  <div class="wrapper">
    <nav style="padding: 2vh 1.3vh; display: flex; justify-content: center;">
      <RouterLink to="/" style="padding: 10px;">
        ホーム
      </RouterLink>
      <RouterLink to="/settings" style="padding: 10px;">
        せってい
      </RouterLink>
    </nav>
  </div>
  <RouterView />
</template>

<style scoped></style>