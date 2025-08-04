<script setup lang="ts">
defineProps({
  name: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="hello-remote">
    👋 Hello <span class="name">{{ name }}</span> from Remote App
  </div>
</template>

<style scoped>
.hello-remote {
  border: 1px dashed blue;
  padding: 1rem;
  margin: 1rem 0;
}
.hello-remote .name {
  font-weight: 700;
}
</style>