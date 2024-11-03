<!-- views/AboutUsView.vue -->
<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import AboutUs from '@/components/AboutUs.vue'
import Join from '@/components/Join.vue'
</script>

<template>
  <MainLayout>
    <AboutUs/> <!-- Menampilkan isi dari komponen AboutUs.vue di dalam MainLayout -->
    <Join/>
  </MainLayout>
</template>