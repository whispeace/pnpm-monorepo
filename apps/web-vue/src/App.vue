<script setup lang="ts">
import UtilList from "@/components/UtilList.vue";
import FloatLabel from "primevue/floatlabel";
import InputText from "primevue/inputtext";
import {ref} from "vue";

const value = ref(null);
</script>

<template>
  <div>
    <UtilList />
    <FloatLabel>
      <InputText id="username" v-model="value" />
      <label for="username">Username</label>
    </FloatLabel>
  </div>
</template>