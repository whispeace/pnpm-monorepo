<script setup lang="ts">
import { utils } from '@utils'
</script>

<template>
  <ul>
    <li v-for="item in utils" :key="item">{{ item }}</li>
  </ul>
</template>