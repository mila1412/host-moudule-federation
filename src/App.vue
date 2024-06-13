<template>
  <div>
    <Content />
    <Content />
    <Button />
    <Button />
  </div>
</template>

<script setup>
import { defineAsyncComponent } from 'vue';
const Content = defineAsyncComponent(() => import("home/Content"));
const Button = defineAsyncComponent(() => import("home/Button"));
</script>

<style scoped></style>
