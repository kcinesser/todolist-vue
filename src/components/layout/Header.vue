<template>
  <header class="header">
    <h1>ToDo List</h1>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </header>
</template>

<script>
export default {
  name: "header",
};
</script>

<style scoped>
#nav a.router-link-exact-active {
  color: #42b983;
}

.header {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 30px;
}

.header a {
  color: #fff;
  padding-right: 5px;
}
</style>