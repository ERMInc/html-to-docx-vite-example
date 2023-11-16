<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import HTMLtoDOCX from 'html-to-docx'

const fileBuffer = await HTMLtoDOCX("<html></html>", null, {footer:true});
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
