<template>
  <router-view />
</template>

<script setup lang="ts">
// import { ref } from 'vue'

const tg = window.Telegram.WebApp

// const isLoading = ref(true)

tg.ready()
</script>

<style lang="scss" scoped></style>
