<template>
  <button :style="'color: ' + color + ';'">xy测试按钮</button>
</template>
<script setup>
const props = defineProps({
  color: {
    type: String,
    default() {
      return "blue";
    },
  },
});
</script>
