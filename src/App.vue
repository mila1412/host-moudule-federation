<template>
  <div>
    <Content />
    <Button />
  </div>
</template>

<script setup>
import { defineAsyncComponent } from 'vue';
const Content = defineAsyncComponent(() => import("home/Content"));
const Button = defineAsyncComponent(() => import("home/Button"));
console.log('test3')
</script>

<style scoped></style>
