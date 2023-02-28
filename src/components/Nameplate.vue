<script setup lang="ts"></script>

<template>
  <h1 class="fullname"><span class="name-text">Joshua Newell Diehl</span></h1>
</template>

<style scoped>
.fullname {
  display: flex;
  align-items: center;
  font-size: 1rem;
  letter-spacing: 0.15rem;
  margin: 1rem auto;
}

.fullname::before {
  content: "<";
  position: relative;
  color: cyan;
  margin-right: 0.11rem;
}

.fullname::after {
  color: cyan;
  content: ">";
  position: relative;
  margin-left: 0.11rem;
}
</style>
