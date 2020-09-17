<template>
  <button @click="click()">{{content}}</button>
</template>

<script>
export default {
  name: "Button",
  props: ["content", "click"],
};
</script>

<style scoped>
</style>