<script setup lang="ts">
import Nameplate from "./Nameplate.vue";
</script>

<template>
  <header class="header">
    <Nameplate />
  </header>
</template>

<style scoped>
.header {
  display: flex;
  text-align: center;
  justify-content: center;
  background-color: #3a3a3a90;
  border-radius: 0 0 3px 3px;
  margin: 0 16.6%;
  box-shadow: 0px 0px 15px 2px rgba(30, 30, 30, 0.324);
}
</style>
