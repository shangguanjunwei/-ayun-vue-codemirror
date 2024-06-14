<template>
  <div>
    <AYunCodeMirror v-model="jsonData" lang="sql" />
  </div>
</template>

<script setup lang="ts">
import AYunCodeMirror from '@/components/AYunCodemirror';
import { ref } from 'vue';

const jsonData = ref<any>('');
</script>

<style scoped lang="less"></style>