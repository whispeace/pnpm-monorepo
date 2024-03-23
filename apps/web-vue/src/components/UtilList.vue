<script setup lang="ts">
import { utils } from '@utils'
</script>

<template>
  <ul>
    <li v-for="item in utils" :key="item" class="text-sm text-gray-700">{{ item }}</li>
  </ul>
</template>