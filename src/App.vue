<template>
  <div id="app">
    <router-link to="/">HOME</router-link>
    <br>
    <router-link to="/foo">Перейти к Foo</router-link>
    <br>
    <router-link to="/bar">Перейти к Bar</router-link>
    <br>
    <router-link to="/posts">Posts</router-link>
    <br>
    <router-link to="/posts/1">Post</router-link>
    <br>
    <br>

    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  created() {
    console.log(this)
  },
  components: {
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
