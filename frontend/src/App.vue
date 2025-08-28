<template>
  <div>
    <h1>Hello from Vue.js!</h1>
    <p>This is a containerized Vue app served by Apache.</p>
  </div>
  <my-test></my-test>
</template>

<script>
import MyTest from './components/my-test.vue';
export default {
  name: 'App',
  components: {
    MyTest,
  }
};
</script>

<style lang="scss">
// Your component-specific styles
</style>
