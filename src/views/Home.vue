<template>
  <div class="home">
    <img id="author" alt="Vue logo" src="../assets/author.jpg">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

#author {
  width: 50vmin;
}

</style>