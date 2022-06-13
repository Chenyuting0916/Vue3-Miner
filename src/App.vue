<template>
  <div>{{ Name }}</div>
  <div>{{ price1 + price2 }}</div>
</template>

<script>
export default {
  name: 'App',
  data: function () {
    return {
      Name: "hi",
      price1: 5,
      price2: 63
    };
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
