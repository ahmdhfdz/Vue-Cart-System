<script setup lang="ts">
defineProps<{
  msg: string;
  name?: string;
}>();
</script>

<template>
  <div>
    {{ (msg, name) }}
  </div>
</template>
