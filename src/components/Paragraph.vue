<script setup lang="ts">
defineProps<{ paragraphMsg: string }>();
</script>

<template>
  <div>
    <p>{{ paragraphMsg }}</p>
  </div>
</template>
