<script lang="ts" setup>
const isLoggedIn = false
const layout = isLoggedIn ? 'auth' : 'guest'
</script>

<template>
  <NuxtLayout :name="layout">
    <NuxtPage />
  </NuxtLayout>
</template>
