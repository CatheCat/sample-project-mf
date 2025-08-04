<script setup lang="ts">

import { defineAsyncComponent } from 'vue'
const HelloRemote = defineAsyncComponent(() => import('remote_app/HelloRemote'))

</script>

<template>
  <h1>You did it!</h1>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>
  <HelloRemote name="Catherine"/>
  <HelloRemote name="Jenny"/>
</template>

<style scoped></style>
