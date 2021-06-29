<template>
  <div id="app">
    <nav>
      <h1>Welcome on my first Vue page</h1>
      <NavLink url="/" text="Home" />
      <NavLink url="/about" text="About" />
      <NavLink url="/contact" text="Contact" />
    </nav>
  </div>
</template>

<script>
import NavLink from'./components/HomeLink.vue'

export default {
  name: 'App',
  components: {
    NavLink
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
