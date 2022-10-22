<template>
  <router-view />
</template>

<script setup lang="ts">
// import { ref } from 'vue'

const tg = window.Telegram.WebApp

tg.ready()
</script>

<style lang="scss" scoped></style>
