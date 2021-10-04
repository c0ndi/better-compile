<template>
  <span class="nav-text-part" :style="{ color: color }">{{ msg }}</span>
</template>

<script setup>
defineProps({
  msg: String,
  color: String,
  fontWeight: String,
});
</script>
