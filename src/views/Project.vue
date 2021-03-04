<template>
  <div class="project">
    <h1>This is an 99 page</h1>
        <table> 
            <thead> 
                <tr> <th>Name</th> <th>link</th>  <th>dis</th> </tr> 
            </thead> 
            <tbody id="stocksTerminal"> 
                <tr v-for="p in projects" :key="p.name"> <td>{{ p.name }}</td> 
                <td><a :href="p.link" target="_blank"> {{ p.link }} </a> </td> </tr> 
            </tbody> 
        </table>
  </div>
</template>

<script>      
  export default {
 name: 'project',
 data ()  {
  return {
    projects: [
        { name: 'p1', link: 'https://www.github.com/kingston0420/' },
        { name: 'p2', link: 'https://www.github.com/kingston0420/' }
    ]
    }
  }
 }
</script>

<style scoped>
  table, th, td {
    border: 3px solid black;
    padding: 1em;
  }

  table {
    border-collapse: collapse;
    margin: 0 auto;
  }

    th {
        background-color: #FCF;
    }
</style>