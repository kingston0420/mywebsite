<template>
  <div class="project">
    <h1>My Project</h1>
        <table> 
            <thead> 
                <tr> <th>Name</th> <th>Language</th> <th>Sorce Code</th>  <th>Discription</th> </tr> 
            </thead> 
            <tbody id="stocksTerminal"> 
                <tr v-for="p in projects" :key="p.name"> 
                  <td>{{ p.name }}</td>
                  <td>{{p.language}}</td> 
                  <td><a :href="p.link" target="_blank"> {{ p.link }} </a> </td> 
                  <td>{{p.discription}}</td>
                </tr> 
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
        { name: 'Unquote', language: 'Java, Android Studio', link: 'https://www.github.com/kingston0420/', discription: 'Unquote is an android game that the player can guess who the quote come from'},
        { name: 'Lineargression', language: 'Python', link: 'https://github.com/kingston0420/Python-Linear_Regression', discription: 'test' },
        { name: 'LCD with LED', language: 'C', link: 'https://github.com/kingston0420/ELEC-291-/tree/master/Lab1', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking' }
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