<script setup lang="ts">
import Plug from '../components/Plug.vue'
import { RouterLink } from 'vue-router'
</script>

<template>
  <div class="plug-page">
    <Plug msg="Dream come true" />
    <RouterLink to="/home" class="start-link">начни исполнять свои желания</RouterLink>
  </div>
</template>

<style scoped>
.start-link {
  display: inline-block;
  margin-top: 20px;
  font-weight: bold;
  color: #2baeb1;
  text-decoration: none;
}
</style>
