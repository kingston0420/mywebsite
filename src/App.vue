<template>
  <div class="back" :class = "{dark: dark}">
    <div class="ui menu">
      <router-link class="item" to="/">Home</router-link>
      <router-link class="item" to="/about">About</router-link>
      <router-link class="item" to="/Project">Project</router-link>
      <router-link class="item" to="/Resume">Resume</router-link>
      <div class="item">
        <input type="checkbox" v-model="dark"/> dark mode
      </div>
    </div>
    <div>
      <router-view/>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'App',
    data() {
      return {
        dark: false
    }
  }
}
</script>

<style>

html, body {
  padding: 0;
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.dark { 
  background-color: black;
  color: white;
}

.back {
  width: 100vw;
  height: 100vh;
  overflow: scroll;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

a.router-link-exact-active {
  background-color: #42b983 !important;
}
</style>
