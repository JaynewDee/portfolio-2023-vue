<script setup lang="ts">
import { ref } from "vue";
import Header from "./components/Header.vue";
import projectData from "./data/projects";
const projects = ref(projectData);
</script>

<template>
  <Header />
</template>

<style scoped></style>
