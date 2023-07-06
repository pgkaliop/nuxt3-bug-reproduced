<template>
  <div class="error">
    <second></second>
  </div>
</template>

<script setup lang="ts">
type Props = {
  error: Record<string, unknown> | string;
};

const props = defineProps<Props>();
</script>

<style scoped lang="scss">
.error {
  border: 1px solid red;
}
</style>
