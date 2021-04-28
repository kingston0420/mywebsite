<template>
  <div class="home">
    <a href="https://www.linkedin.com/in/kingstonchen/" target="_blank" rel="noopener noreferrer"><i class="linkedin icon"/></a>
    <a href="https://github.com/kingston0420" target="_blank" rel="noopener noreferrer"><i class="github icon"/></a>
    <a href="mailto:kingston.jy.chen@gmail.com" target="_blank" rel="noopener noreferrer"><i class="envelope icon"/></a>
    <h1>Hello, I'm Kingston Chen</h1>
    <h2>Welcome to my website</h2>
    <p> I am an undergraduate student studying Electrical Engineering at the University of British Columbia with a strong interest in software development. 
        My technical work experiences include: Application Enginner at Maxim Integrated and Network/Software Engineer at Bell Canada. 
        Here, you will find out more about me, my projects, and my hobbies. 
    </p>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    props: {
      msg: String
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
    text-decoration: none;
  }
  p {
    max-width: 800px;
    margin: 20px auto;
    text-align: left;
  }
</style>
