<script>
export default {
  data() {
    return {
      count: 0,
    };
  }
}
</script>

<template>
<button @click="count++">Count: {{count}}</button>
</template>

<style scoped>
button: {
  font-weight: bold;
  color: red;
}
</style>