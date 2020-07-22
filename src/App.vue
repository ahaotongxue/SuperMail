<template>
  <div id="app">
    <h2>{{message}}</h2>
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
  data() {
    return {
      message: "hello world"
    };
  }
};
</script>

<style>
@import "./assets/css/base.css";
</style>
