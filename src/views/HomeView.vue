<!-- views/HomeView.vue -->
<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import Home from '@/components/Home.vue'
import Join from '@/components/Join.vue'
</script>

<template>
  <MainLayout>
    <Home /> <!-- Menampilkan isi dari komponen Home.vue di dalam MainLayout -->
    <Join/>
  </MainLayout>
</template>

