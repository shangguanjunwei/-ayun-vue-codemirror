<template>
  <div>
    <AYunCodeMirror v-model="jsonData" lang="javascript" />
  </div>
</template>

<script setup lang="ts">
import AYunCodeMirror from './components/AYunCodemirror/index.vue';
import { ref } from 'vue';

const jsonData = ref<any>('');
</script>

<style scoped lang="less"></style>