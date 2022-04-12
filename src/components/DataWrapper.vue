<script setup lang="ts">
const data = {
  title: 'Data Wrapper',
  description: 'A wrapper for data',
  data: {
    name: 'John Doe',
    age: 30,
    address: {
      street: '123 Main St',
      city: 'Anytown',
      state: 'CA'
    }
  }
}
</script>

<template>
  <slot :values="data"></slot>
</template>