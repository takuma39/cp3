<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import Header from '@/components/layouts/HeaderLayout.vue';
import Footer from '@/components/layouts/FooterLayout.vue';
import PageTop from '@/components/layouts/PageTopLayout.vue';
</script>

<template>
  <Header />
  <RouterView />
  <Footer />
  <PageTop />
</template>

<style scoped lang="scss"></style>
