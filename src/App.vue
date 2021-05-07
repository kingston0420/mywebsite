<template>
  <div class="back" :class = "{dark: dark}">
    <div class="ui menu">
      <router-link class="item" to="/"><i class="home icon"/>Home</router-link>
      <router-link class="item" to="/about"><i class="address card icon"/>About</router-link>
      <router-link class="item" to="/Project"><i class="folder icon"/>Project</router-link>
      <router-link class="item" to="/Resume"><i class= "file alternate icon"/>Resume</router-link>
      <div class="item">
        <input type="checkbox" v-model="dark"/><i class="moon icon"/>Dark Mode
      </div>
    </div>
    <div>
      <router-view :dark="dark"/>
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

.dark table, .dark th, .dark td {
  border: 3px solid white !important; 
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
