<template>
  <div class="test-comp">
    {{ props.id }}
  </div>
</template>

<script setup lang='ts'>
import { ITestCompProps } from '../types/test';

const props = defineProps<ITestCompProps>()
</script>

<style lang="scss" scoped>
  .test-comp{

  }
</style>