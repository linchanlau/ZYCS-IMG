<template>
  <Header title="V金数据图床" />
  <main><RouterView /></main>
  <Toaster />
</template>
<script setup lang="ts">
import Header from '@/components/Header/Header.vue';
import { Toaster } from '@/components/ui/toast';
</script>

<style scoped></style>
