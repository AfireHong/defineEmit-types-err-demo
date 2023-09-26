<script lang="ts" setup>
const emits = defineEmits<{
  (e: "do-something"): void;
}>();
</script>
<template>
  <div>
    <button @click="$emit('do-something')">demo</button>
  </div>
</template>
<style lang="stylus" scoped></style>
