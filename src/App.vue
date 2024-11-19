<script setup lang="ts">
import { useRoute } from "vue-router";
const route = useRoute();
</script>

<template>
  <div id="avisos"><strong>Current route path:</strong> {{ route.params }}</div>
</template>
