<template>
    <nav>
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </nav>
</template>

<script>
export default {
  name: 'navBar',
  props: {
    msg: String,
  },
};
</script>

<style scoped>

</style>