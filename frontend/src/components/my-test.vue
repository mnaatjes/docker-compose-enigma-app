<template>
  <div class="my-test">
    <p class="component-text">{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: 'MyTest',
  data() {
    return {
      message: 'Hello, Vue Component!',
    };
  },
};
</script>

<style scoped>
.my-test {
  color: #42b983;
}
</style>