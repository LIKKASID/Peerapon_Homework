<template>
  <div id="app">
    <router-link class="link" :to="{ path: '/Profile' }">Profile</router-link>
    <router-link class="link" :to="{ path: '/Contact' }">Contact</router-link>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  margin: 0px;
}
.link {
  display: inline-block;
  padding: 10px;
  text-decoration: none;
  color: inherit;
  font-size: 18px;
}
.router-link-exact-active {
  color: blue;
}
body {
  background-color: #90969d;
}
</style>
