<template>
  <div class="project">
    <h1>My Project</h1>
        <table> 
            <thead> 
                <tr> <th>Name</th> <th>Software</th> <th>Sorce Code</th>  <th>Discription</th> </tr> 
            </thead> 
            <tbody id="stocksTerminal"> 
                <tr v-for="p in projects" :key="p.name"> 
                  <td>{{ p.name }}</td>
                  <td>{{p.software}}</td> 
                  <td><a :href="p.link" target="_blank"> {{ p.link }} </a> </td> 
                  <td class="dis">{{p.discription}}</td>
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
        { name: 'DH Game', software: 'VueJs', link: 'https://github.com/kingston0420/dhgame', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking'},
        { name: 'Unquote', software: 'Java', link: 'https://github.com/kingston0420/UnquoteAndroidApp', discription: 'Unquote is an android game that the player can guess who the quote come from'},
        { name: 'LeetCode', software: 'Java', link: 'https://github.com/kingston0420/LeetCode', discription: 'This is to document my progress and solutions to interview question on LeetCode'},
        { name: 'This Website', software: 'VueJs', link: 'https://github.com/kingston0420/mywebsite', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking'},
        { name: 'Greedy Snake', software: 'Python', link: 'https://github.com/kingston0420/GreedySnake', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking'},
        { name: 'ELEC 331', software: 'Python', link: 'https://github.com/kingston0420/ELEC-331-NetworkPing', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking'},
        { name: 'ELEC 291', software: 'C, Assembly', link: 'https://github.com/kingston0420/ELEC-291-', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking'},
        { name: 'Excursion Website', software: 'HTML, CSS', link: '//github.com/kingston0420/Excursion-Project', discription: 'Using Microcontroller and circuit to display messageon the LCD and control LED blinking'}
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
    max-width: 800px; 
    box-shadow: 0px 5px 5px 0px #9B8F99;
    white-space: nowrap;
  }
  .dis {
    white-space: normal;
  } 

  th {
      background-color: #FCF;
  }


</style>