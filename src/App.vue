<script setup lang="ts">
import DataWrapper from '@/components/DataWrapper.vue'
</script>

<template>
  <DataWrapper v-slot="{ values }">
    data: {{ values }}
  </DataWrapper>
</template>