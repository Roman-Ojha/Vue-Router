<template>
  <div>
    <h1>{{ $route.params.id }} Home Page</h1>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "Home",
});
</script>

<style scoped></style>
