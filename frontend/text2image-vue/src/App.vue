<template>
  <div id="app">
    <nav>
      <router-link to="/about" class="nav-link">About</router-link>
      <router-link to="/login" class="nav-link">Login</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  display: flex;
  justify-content: center;
}

.nav-link {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  margin: 0 15px;
  transition: color 0.3s ease;
}

.nav-link:hover,
.nav-link.router-link-exact-active {
  color: #42b983;
}

</style>
