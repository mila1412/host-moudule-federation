<template>
  <div>
    <Content />
    <Button />
    <Button />
  </div>
</template>

<script setup>
import { defineAsyncComponent } from 'vue';
const Content = defineAsyncComponent(() => import("home/Content"));
const Button = defineAsyncComponent(() => import("home/Button"));
console.log('test')
</script>

<style scoped></style>
