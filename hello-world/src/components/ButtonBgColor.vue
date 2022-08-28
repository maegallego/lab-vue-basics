<template>
  <Button
    v-bind:class="{ white: active, blue: hover }"
    >Change color</Button
  >
</template>

<style scoped>
.white {
  background-color: white;
  width: 200px;
  height: 200px;
}
.blue {
  width: 200px;
  height: 200px;
  background-color: blue;
}
</style>
