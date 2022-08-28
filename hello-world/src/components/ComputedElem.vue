<template>
  <div>
    <p>{{ sum }}</p>
    <p v-if="sum > 5">Greater than 5</p>
  </div>
</template>

<script>
export default {
  data() {
    const num1 = 5;
    return {
      sum: num1 + num1,
    };
  },
};
</script>

<style scoped>
</style>
